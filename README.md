<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-commerce Product Page</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Body Styling */
        body {
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
        }

        /* Navigation Bar */
        nav {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Product Page Layout */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
        }

        /* Product Image */
        .product-image {
            flex: 1 1 40%;
            max-width: 40%;
        }

        .product-image img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        /* Product Details */
        .product-details {
            flex: 1 1 50%;
            max-width: 50%;
        }

        .product-details h1 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .product-details p {
            margin: 0.5rem 0;
        }

        .product-details .price {
            font-size: 1.5rem;
            color: #e91e63;
            margin: 1rem 0;
        }

        /* Add to Cart Button */
        .add-to-cart {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            background-color: #007BFF;
            color: #fff;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .add-to-cart:hover {
            background-color: #0056b3;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
                align-items: center;
            }

            .product-image, .product-details {
                max-width: 100%;
                text-align: center;
            }

            .product-details .add-to-cart {
                width: 100%;
            }
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">MyShop</div>
        <div class="links">
            <a href="#">Home</a>
            <a href="#">Shop</a>
            <a href="#">Contact</a>
        </div>
    </nav>

    <!-- Product Page Content -->
    <div class="container">
        <!-- Product Image -->
        <div class="product-image">
            <img src="https://via.placeholder.com/500" alt="Product Image">
        </div>

        <!-- Product Details -->
        <div class="product-details">
            <h1>Product Name</h1>
            <p>This is a detailed description of the product. It highlights the key features and benefits of the item.</p>
            <p class="price">$49.99</p>
            <button class="add-to-cart">Add to Cart</button>
        </div>
    </div>

</body>
</html>
