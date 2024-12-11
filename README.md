# Ex.07 Restaurant Website
# Date: 08.12.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
res.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EAT AND MEAT</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #4ec32a;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav {
            margin: 15px 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2.5em;
        }
        .burger-gallery {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 20px;
        }
        .burger-item {
            text-align: center;
        }
        .burger-item img {
            width: 100%;
            border-radius: 8px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #51f542;
            color: white;
            /* position: absolute;
            bottom: 0; */
            width: 100%;
        }
        .btn {
            background-color: #68df39;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
        .btn:hover {
            background-color: #3fed32;
        }
    </style>
</head>
<body>
    <header>
        <h1>EAT AND MEAT</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="order.html">Order Now</a>
        </nav>
    </header>
        <center>
        <h2 style="font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;">today offers</h2>
        </center>
        <div class="burger-gallery">
            <div class="burger-item">
                <img src="vegbur.png" alt="cheese veg burger" style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">cheese veg burger</p>
            </div>
            <div class="burger-item">
                <img src="mushroom.png" alt="mushroom burger" style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">mushroom burger</p>
            </div>
            <div class="burger-item">
                <img src="chicken.png" alt="chicken burger" style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">chicken burger</p>
            </div>
            <div class="burger-item">
                <img src="truffle.png" alt="truffle burger"style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">truffle burger</p>
            </div>
            <div class="burger-item">
                <img src="cheese veg pizza.png" alt="cheese veg pizza" style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">cheese veg pizza</p>
            </div>
            <div class="burger-item">
                <img src="mushroom pizza.png" alt="mushroom pizza" style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">mushroom pizza</p>
            </div>
            <div class="burger-item">
                <img src="chicken pizza.png" alt="chicken pizza" style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">chicken pizza</p>
            </div>
            <div class="burger-item">
                <img src="panner pizza.png" alt="panner pizza"style="height: 400px;">
                <p style="font-family: Verdana, Geneva, Tahoma, sans-serif;">panner pizza</p>
            </div>
        </div>
        </div>
    </div>

</body>
</html>

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Restaurant Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 30px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            font-size: 1.8em;
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-group button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }
        .form-group button:hover {
            background-color: #555;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #333;
            color: white;
        }
        .actions button {
            padding: 6px 12px;
            background-color: #f44336;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 4px;
        }
        .actions button:hover {
            background-color: #e53935;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Restaurant Administration</h1>
        <p>Manage your restaurant operations</p>
    </header>

    <!-- Navigation Menu -->
    <nav>
        
        <a href="home.html">Menu Management</a>
        <a href="menu.html">Reservations</a>
        <a href="order.html">Orders</a>
    </nav>

</body>
</html>


menu.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENU</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #6ef431;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #69d029;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>EAT AND MEAT</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="order.html">Order Now</a>
        </nav>
    </header>
    <center>
        <!-- Menu Section -->
        <section id="menu" class="menu">
            <h1>OUR MENU</h1>
                <ul>cheese veg burger - ₹499</ul><br>
                <ul>mushroom burger - ₹499</ul><br>
                <ul>chicken burger - ₹549</ul><br>
                <ul>truffle burger - ₹599</ul><br>
                <ul>cheese veg pizza - ₹499</ul><br>
                <ul>mushroom pizza - ₹499</ul><br>
                <ul>chicken pizza - ₹549</ul><br>
                <ul>panner pizza - ₹549</ul><br>
        </section>
    </center>
</body>
</html>

order.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order Now - burger kings</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #6ef431;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #69d029;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>EAT AND MEAT</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="order.html">Order Now</a>
        </nav>
    </header>

    <div class="container">
        <h1>your order</h1>
        <p>free unlimited pepsi over ₹1500</p>
        <form>
            <label for="burger">choose:</label>
            <select id="burger" name="burger">
                <option value="cheese veg burger">cheese veg pizza</option>
                <option value="mushroom burger">mushroom burger</option>
                <option value="chicken burger">chicken burger</option>
                <option value="truffle burger">truffle burger</option>
                <option value="cheese veg pizza">cheese veg burger</option>
                <option value="mushroom pizza">mushroom pizzar</option>
                <option value="chicken pizza">chicken pizza</option>
                <option value="panner pizza">panner pizza</option>
            </select><br><br>

            <input type="submit" value="Place Order">
        </form>
    </div>
    <footer>
        &copy; EAT AND MEAT since 1998. All Rights Reserved.
    </footer>

</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order Now - burger kings</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }
        header {
            background-color: #6ef431;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #69d029;
            color: white;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>EAT AND MEAT</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="order.html">Order Now</a>
        </nav>
    </header>

    <div class="container">
        <h1>your order</h1>
        <p>free unlimited pepsi over ₹1500</p>
        <form>
            <label for="burger">choose:</label>
            <select id="burger" name="burger">
                <option value="cheese veg burger">cheese veg pizza</option>
                <option value="mushroom burger">mushroom burger</option>
                <option value="chicken burger">chicken burger</option>
                <option value="truffle burger">truffle burger</option>
                <option value="cheese veg pizza">cheese veg burger</option>
                <option value="mushroom pizza">mushroom pizzar</option>
                <option value="chicken pizza">chicken pizza</option>
                <option value="panner pizza">panner pizza</option>
            </select><br><br>

            <input type="submit" value="Place Order">
        </form>
    </div>
    <footer>
        &copy; EAT AND MEAT since 1998. All Rights Reserved.
    </footer>

</body>
</html>
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/442e97dc-0048-4868-984a-239717ebe94d)
![image](https://github.com/user-attachments/assets/824e9e52-5a41-4c13-a745-d0dbde8333f8)
![image](https://github.com/user-attachments/assets/75f12ee8-96bc-4275-93a0-1c6880036aa7)
![image](https://github.com/user-attachments/assets/622da643-64f9-4542-b9ee-d18e944d0673)
![image](https://github.com/user-attachments/assets/45b09de3-6f5c-4f95-afb4-fa34e5e89a02)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
