# Ex.06 Restaurant Website
## Date:25-04-25

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
HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Little Lemon Logo">
            <h1>Little Lemon</h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Book</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner" style="background-image: url('offer.webp');">
            <h2 class="offer-txt">30% Off This Weekend</h2>
            <p class = 'offer-txt'>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Our New Menu</h3>
                <img src="menu.jpeg" alt="Our New Menu">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="www.google.com">See our new menu</a>
            </div>
            <div class="feature">
                <h3>Book a table</h3>
                <img src="book.jpeg" alt="Book a table">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices. Duis at varius ligula. Integer pulvinar tempus quam, et consequat nulla viverra in. Nullam ut tortor magna. Nulla eget placerat leo. Nunc eu finibus magna, sed vulputate magna.</p>
                <a href="www.google.com">Book your table now</a>
            </div>
            <div class="feature">
                <h3>Opening Hours</h3>
                <img src="hours.jpeg" class="hours" alt="Opening Hours">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse et congue massa, eu fringilla mauris. Fusce dapibus vehicula ex at ultrices.</p>
                <ul>
                    Monday - Friday: 11:00 AM - 10:00 PM <br>
                    Saturday: 10:00 AM - 11:00 PM <br>
                    Sunday: 10:00 AM - 9:00 PM <br>
                </ul>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="footer.png" class="footer" alt="Little Lemon Logo">
                <p class="copy">&copy; Copyright Little Lemon</p>
            </div>
        </footer>
    </main>
</body>
</html>
```
CSS
```
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #b9fbe9;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: rgb(162, 211, 176);
    border-radius: 10px;
}

.menu{
    background-color: black;
    color: rgb(250, 4, 4);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 80px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.offer-txt{
    color: black;
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background: url('banner.jpg') no-repeat center center/cover;
    padding: 60px 20px;
    color: #fff;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(162, 211, 176);
}

.feature {
    text-align: center;
    background-color: rgb(240, 202, 133);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: blue;
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/a54043f4-8ede-4c12-ac55-a3d5d8f2176a)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
