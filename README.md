<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        .menu-container {
            max-width: 900px;
            margin: 20px auto;
            background-color: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 6px 12px rgba(0,0,0,0.1);
        }

        h1 {
            text-align: center;
            color: #4CAF50;
            margin-bottom: 30px;
        }

        .category {
            margin-bottom: 30px;
        }

        .category h2 {
            color: #333;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }

        .dish {
            display: flex;
            justify-content: space-between;
            margin-bottom: 12px;
            padding-bottom: 8px;
            border-bottom: 1px dotted #ccc;
        }

        .dish-name {
            font-weight: bold;
            color: #555;
        }

        .dish-price {
            color: #4CAF50;
        }

        @media (max-width: 600px) {
            .dish {
                flex-direction: column;
                align-items: flex-start;
            }

            .dish-price {
                margin-top: 5px;
            }
        }
    </style>
</head>
<body>
    <div class="menu-container">
        <h1>Our Menu</h1>

        <div class="category">
            <h2>Appetizers</h2>
            <div class="dish">
                <span class="dish-name">Spring Rolls</span>
                <span class="dish-price">₹350</span>
            </div>
            <div class="dish">
                <span class="dish-name">Garlic Bread</span>
                <span class="dish-price">₹250</span>
            </div>
        </div>

        <div class="category">
            <h2>Main Course</h2>
            <div class="dish">
                <span class="dish-name">Grilled Chicken</span>
                <span class="dish-price">₹900</span>
            </div>
            <div class="dish">
                <span class="dish-name">Pasta Alfredo</span>
                <span class="dish-price">₹750</span>
            </div>
        </div>

        <div class="category">
            <h2>Desserts</h2>
            <div class="dish">
                <span class="dish-name">Chocolate Cake</span>
                <span class="dish-price">₹400</span>
            </div>
            <div class="dish">
                <span class="dish-name">Ice Cream Sundae</span>
                <span class="dish-price">₹350</span>
            </div>
        </div>

        <div class="category">
            <h2>Drinks</h2>
            <div class="dish">
                <span class="dish-name">Coca Cola</span>
                <span class="dish-price">₹100</span>
            </div>
            <div class="dish">
                <span class="dish-name">Orange Juice</span>
                <span class="dish-price">₹120</span>
            </div>
        </div>
    </div>
</body>
</html>
