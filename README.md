# Ex.07 Restaurant Website
## Date:23/12/2024

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
```

table.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SUPERSTAR foods</title>
    <style>
        body {
            background-color: rgb(82, 220, 238);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color:rgb(91, 136, 226);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color:rgb(84, 94, 166);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color:rgb(96, 135, 207);
        }
        .hero {
             background-color:rgb(18, 132, 145);
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            border: 1px solid rgb(51, 170, 103);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color:rgb(240, 247, 115);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>SUPERSTAR foods</h1>
    </header>
    <nav>
        <a href="home.html">home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to Our Restaurant</h1>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about serving delicious food made with fresh ingredients. Join us for an unforgettable dining experience!</p>
    </section>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu">
                <div class="menu-item">
                    <img src="dosa.avif" alt="DOSA">
                    <h3>DOSA</h3>
                    <p>Crispy, golden dosas with a perfect blend of tradition and flavor, served with mouthwatering accompaniments.</p>
                </div>
                <div class="menu-item">
                    <img src="noodles.jpg" alt="NOODLES">
                    <h3>NOODLES</h3>
                    <p> Serving delicious, handcrafted noodles with bold flavors and fresh ingredients to satisfy every craving.</p>
                </div>
                <div class="menu-item">
                    <img src="chappati.jpg" alt="CHAPPATI">
                    <h3>CHAPPATI</h3>
                    <p>Freshly made, soft, and wholesome chapatis crafted to perfection for a truly authentic taste.</p>
                </div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone:8115481154</p>
        <p>Email:Tuntunfoods@gmail.com</p>
        <p>Address: 27 middle Street,sigma road ,bangalore</p>
    </section>
    <footer>
        <p>&copy; DINESH S. All Right Reserved.</p>
    </footer>
</body>
</html>



menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - TUNTUN FOODS</title>
    <style>
        body {
            background-color: rgb(213, 166, 181);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(171, 106, 151);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(187, 85, 186);
        }
        nav a {
            color: rgb(248, 97, 97);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(137, 28, 135);
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid silver;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: rgb(181, 41, 146);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Our Menu</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Explore Our Dishes</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="dosa.avif" alt="DOSA">
                <h3>DOSA</h3>
                <p>Crispy, golden dosas with a perfect blend of tradition and flavor, served with mouthwatering accompaniments. </p>
            </div>
            <div class="menu-item">
                <img src="noodles.jpg" alt="NOODLES">
                <h3>NOODLES</h3>
                <p> Serving delicious, handcrafted noodles with bold flavors and fresh ingredients to satisfy every craving.</p>
            </div>
            <div class="menu-item">
                <img src="chappati.jpg" alt="CHAPPATI">
                <h3>CHAPPATI</h3>
                <p>Freshly made, soft, and wholesome chapatis crafted to perfection for a truly authentic taste.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; TUNTUN FOODS. All Right Reserved.</p>
        <p> designed and developed by: DINESH S</p>
    </footer>
</body>
</html>



index.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - TUNTUN FOODS</title>
    <style>
        body {
            background-color: rgb(79, 164, 210);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(116, 206, 239);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(82, 170, 187);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(73, 163, 181);
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid silver;
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: rgb(4, 114, 6);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to TUNTUN FOODS</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>TUNTUN Foods offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy;TUNTUN FOODS. All Right Reserved.</p>
        <p> designed and developed by: DINESH S</p>
    </footer>
</body>
</html>


contact.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - TUNTUN FOODS</title>
    <style>
        body {
            background-color: rgb(213, 171, 80);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(186, 174, 112);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(202, 192, 48);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(191, 194, 47);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: rgb(199, 206, 60);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>A warm welcome</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong>8115481154</p>
            <p><strong>Email:</strong> Tuntunfoods@gmail.com</p>
            <p><strong>Address:</strong> 27 middle Street, sigma road , bangalore</p>
            <p>we value your feedback</p>
    </section>
    <footer>
        <p>&copy; TUNTUN FOODS. All Right Reserved.</p>
        <p> designed and developed by: DINESH S</p>
    </footer>
</body>
</html>


about.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - TUNTUN FOODS</title>
    <style>
        body {
            background-color: rgb(191, 193, 94);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(83, 171, 16);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(145, 185, 87);
        }
        nav a {
            color: rgb(95, 192, 227);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(177, 206, 33);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
            text-align: justify;
        }
        footer {
            background-color: rgb(146, 227, 116);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About TUNTUN Foods</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Story</h2>
        <div class="content">
            <p>Welcome to TUNTUN Foods, where we bring together a love for fresh, delicious meals and a passion for hospitality. Established with the goal of creating memorable dining experiences, Java Foods is your go-to destination for a delightful culinary journey.</p>
            <p>Our team is committed to using the finest ingredients to prepare dishes that reflect authenticity and innovation. Whether you're here for a hearty meal, a light snack, or a sweet treat, our menu is designed to cater to every craving.</p>
            <p>We take pride in our warm and inviting atmosphere, perfect for family gatherings, friendly get-togethers, or a quiet meal on your own. At Java Foods, we believe food is more than just sustenance—it's an experience, and we are thrilled to share it with you.</p>
        </div>
    </section>
    <footer>
        <p>&copy;TUNTUN Foods. All Right Reserved.</p>
        <p> designed and developed by:SHREE CHANDRU R</p>
    </footer>
</body>
</html>






```
## OUTPUT:
![alt text](<Screenshot (2).png>)
![alt text](<Screenshot (3).png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (6).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
