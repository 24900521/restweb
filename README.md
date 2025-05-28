# Ex.06 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
REST.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title> VIGNEHS 's Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background-color: #121212;
            color: #f0f0f0;
        }
        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            border-bottom: 3px solid #ff9800;
        }
        header img {
            height: 50px;
            vertical-align: middle;
        }
        header h1 {
            display: inline;
            margin-left: 10px;
            color: #ff9800;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2c2c2c;
            padding: 10px;
        }
        nav a {
            color: #f0f0f0;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff9800;
        }
        .banner {
            background-image: url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092');
            background-size: cover;
            background-position: center;
            padding: 60px 20px;
            color: white;
            text-align: center;
        }
        .banner h2 {
            font-size: 2em;
            margin: 0;
            background: rgba(0, 0, 0, 0.6);
            display: inline-block;
            padding: 10px;
        }
        .section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 30px 10px;
            background-color: #181818;
        }
        .card {
            background-color: #2a2a2a;
            width: 300px;
            margin: 15px;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0,0,0,0.7);
        }
        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }
        .card-content {
            padding: 15px;
        }
        .card-content h3 {
            color: #ff9800;
        }
        .card-content p {
            font-size: 0.9em;
            line-height: 1.5;
        }
        footer {
            background-color: #1c1c1c;
            text-align: center;
            padding: 15px;
            color: #ccc;
            font-size: 0.9em;
            border-top: 2px solid #ff9800;
        }
        footer span {
            color: #ff9800;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Logo">
        <h1>VIGENSH 's Restaurant</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#admin">Administration</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <div class="banner">
        <h2>30% Off This Weekend!</h2>
        <p>Enjoy the best dishes with amazing discounts. Book your table now!</p>
    </div>

    <div class="section">
        <div class="card">
            <img src="menu.jpeg" alt="Menu" />
            <div class="card-content">
                <h3>Our New Menu</h3>
                <p>Explore our variety of delicious meals prepared with love and care.</p>
                <a href="#menu" style="color: #ff9800;">See our new menu</a>
            </div>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1543353071-873f17a7a088" alt="Table" />
            <div class="card-content">
                <h3>Book a Table</h3>
                <p>Reserve your spot and enjoy an unforgettable dining experience.</p>
                <a href="#book" style="color: #ff9800;">Book now</a>
            </div>
        </div>
        <div class="card">
            <img src="open.jpeg" alt="Hours" />
            <div class="card-content">
                <h3>Opening Hours</h3>
                <p>Mon - Fri: 2pm - 10pm<br/>Sat: 2pm - 11pm<br/>Sun: 2pm - 9pm</p>
            </div>
        </div>
    </div>

    <footer>
        Designed and Developed by <span>VIGENESH V</span>
    </footer>
</body>
</html>
```
MENU.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Menu - VIGNESH 's Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background-color: #121212;
            color: #f0f0f0;
        }
        header, footer {
            background-color: #1f1f1f;
            text-align: center;
            padding: 20px;
            color: #ccc;
            border-bottom: 3px solid #ff9800;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2c2c2c;
            padding: 10px;
        }
        nav a {
            color: #f0f0f0;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        .menu-section {
            padding: 30px;
            background-color: #181818;
            text-align: center;
        }
        .menu-item {
            background-color: #2a2a2a;
            margin: 15px;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.7);
        }
        .menu-item h3 {
            color: #ff9800;
        }
    </style>
</head>
<body>
    <header>
        <h1>Menu - VIGNESH 's Restaurant</h1>
    </header>
    
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
        <a href="book_now.html">Book Now</a>
    </nav>
    
    <div class="menu-section">
        <h2>Our Delicious Menu</h2>
        <div class="menu-item"><img src="spaghetti.jpg"><h3><p>Spaghetti Carbonara</h3><p>Classic Italian pasta dish with creamy sauce and crispy pancetta.</p></div>
        <div class="menu-item"><img src="margherita pizza.jpeg"><h3><p></p>Margherita Pizza</h3><p>Traditional pizza with tomato sauce, mozzarella, and fresh basil.</p></div>
        <div class="menu-item"><img src="caesar salad.jpg"><h3>Caesar Salad</h3><p>Fresh romaine lettuce with Caesar dressing, croutons, and parmesan.</p></div>
        <div class="menu-item"><img src="grilled salmon.jpeg"><h3>Grilled Salmon</h3><p>Seasoned salmon fillet grilled to perfection, served with vegetables.</p></div>
        <div class="menu-item"><img src="chicken tikka masala.jpeg"><h3>Chicken Tikka Masala</h3><p>Spicy and flavorful chicken in a creamy tomato sauce.</p></div>
        <div class="menu-item"><img src="vegetable stir fry.jpeg"><h3>Vegetable Stir Fry</h3><p>Stir-fried seasonal vegetables served with steamed rice.</p></div>
        <div class="menu-item"><img src="beef tacos.jpeg"><h3>Beef Tacos</h3><p>Soft corn tortillas filled with seasoned beef, topped with salsa.</p></div>
        <div class="menu-item"><img src="chocolate cake.jpeg"><h3>Chocolate Lava Cake</h3><p>Molten chocolate cake served with a scoop of vanilla ice cream.</p></div>
        <div class="menu-item"><img src="cheese burger.jpeg"><h3>Cheeseburger</h3><p>Juicy beef patty with cheese, lettuce, and tomato on a toasted bun.</p></div>
        <div class="menu-item"><img src="fruit salad.jpeg"><h3>Fresh Fruit Salad</h3><p>Assorted seasonal fruits served in a refreshing salad.</p></div>
        <div class="menu-item"><img src="pasta.jpeg"><h3>Pasta Primavera</h3><p>Pasta mixed with fresh vegetables and olive oil.</p></div>
        <div class="menu-item"><img src="lemon tart.jpeg"><h3>Lemon Tart</h3><p>Classic tart with a buttery crust and tangy lemon filling.</p></div>
    </div>
    
    <footer>
        Designed by VIGNESH V
    </footer>
</body>
</html>

```
ADMIN.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Administration - VIGNESH's Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background-color: #121212;
            color: #f0f0f0;
        }
        header, footer {
            background-color: #1f1f1f;
            text-align: center;
            padding: 20px;
            color: #ccc;
            border-bottom: 3px solid #ff9800;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2c2c2c;
            padding: 10px;
        }
        nav a {
            color: #f0f0f0;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        .admin-section {
            padding: 30px;
            background-color: #181818;
            text-align: center;
        }
        .staff-member {
            margin: 15px;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.7);
            background-color: #2a2a2a;
        }
        .staff-member img {
            width: 100px;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Administration - VIGNESH 's Restaurant</h1>
    </header>
    
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
        <a href="book_now.html">Book Now</a>
    </nav>
    
    <div class="admin-section">
        <h2>Meet Our Team</h2>
        <div class="staff-member"><img src="john.jpeg" alt="Staff Member 1"><h3>John Doe</h3><p>Head Chef</p></div>
        <div class="staff-member"><img src="jane.jpeg" alt="Staff Member 2"><h3>Jane Smith</h3><p>Manager</p></div>
        <div class="staff-member"><img src="james.jpeg" alt="Staff Member 3"><h3>James Brown</h3><p>Front of House</p></div>
        <div class="staff-member"><img src="emily.jpeg" alt="Staff Member 4"><h3>Emily Davis</h3><p>Bartender</p></div>
        <div class="staff-member"><img src="michael.jpeg" alt="Staff Member 5"><h3>Michael Wilson</h3><p>Marketing Director</p></div>
        <div class="staff-member"><img src="sarah.jpeg" alt="Staff Member 6"><h3>Sarah Johnson</h3><p>Wait Staff</p></div>
    </div>
    
    <footer>
        Designed by VIGNESH V
    </footer>
</body>
</html>
```
contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contact Us - VIGNESH 's Restaurant</title>
    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background-color: #121212;
            color: #f0f0f0;
        }
        header, footer {
            background-color: #1f1f1f;
            text-align: center;
            padding: 20px;
            color: #ccc;
            border-bottom: 3px solid #ff9800;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2c2c2c;
            padding: 10px;
        }
        nav a {
            color: #f0f0f0;
            margin: 0 20px;
            text-decoration: none;
            font-weight: bold;
        }
        .contact-section {
            padding: 30px;
            background-color: #181818;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us - VIGNESH's Restaurant</h1>
    </header>
    
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="administration.html">Administration</a>
        <a href="contact.html">Contact Us</a>
        <a href="book_now.html">Book Now</a>
    </nav>
    
    <div class="contact-section">
        <h2>Get in Touch</h2>
        <p>Address: 123 Flavor St, Foodie Town</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: contact@vigneshsrestaurant.com</p>
    </div>
    
    <footer>
        Designed by VIGNESH
    </footer>
</body>
</html>
```



## OUTPUT:

![Screenshot 2025-05-28 153616](https://github.com/user-attachments/assets/e3d24882-4b74-4327-9acb-1629b3f596f5)

![Screenshot 2025-05-28 154049](https://github.com/user-attachments/assets/afae7362-64db-41c9-b20d-61844b948d84)

![Screenshot 2025-05-28 154107](https://github.com/user-attachments/assets/08bd892d-de12-4b6c-8e79-6da42a15f292)

![Screenshot 2025-05-28 154147](https://github.com/user-attachments/assets/4547bbf6-28d8-4468-96d2-c9758bdf9484)

![Screenshot 2025-05-28 154916](https://github.com/user-attachments/assets/f9c59fc6-35d8-4d37-a242-633d88dfec5b)

![Screenshot 2025-05-28 154928](https://github.com/user-attachments/assets/451cac0b-9368-4684-bd51-cc4762eb165b)

![Screenshot 2025-05-28 155304](https://github.com/user-attachments/assets/9e74fd7e-ef50-4da3-89e9-acbc24a479b6)




## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
