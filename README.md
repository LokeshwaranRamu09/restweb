# Ex.07 Restaurant Website
## Date:27/12/2024

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CONTINENTAL CAFE CUSINE</title>
    <style>
        /* General Body Styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color:#e5533d;
        }

        /* Header Styling */
        header {
            background: url('rbackground.jpeg') no-repeat center center/cover;
            height: 100vh;
            color:#e5533d;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position: relative;
        }

        header h1 {
            font-size: 3em;
            font-weight: bold;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }

        header ul {
            list-style-type: none;
            padding: 0;
        }

        header ul li {
            display: inline;
            margin-right: 20px;
        }

        header ul li a {
            text-decoration: none;
            color:blue;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        header ul li a:hover {
            color: #ff6347;
        }

        /* Home Section Styling */
        .home-section {
            background-color: rgba(255, 255, 255, 0.9);
            padding: 50px 20px;
            text-align: center;
        }

        .home-section h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
            color: #333;
        }

        .home-section p {
            font-size: 1.5em;
            color: #777;
            margin-bottom: 20px;
        }

        .home-section1 .button {
            background-color: #ff6347;
            padding: 15px 30px;
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .home-section1 .button:hover {
            background-color: #e5533d;
        }

        /* Footer Styling */
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        /* Container for centering content */
        .container {
            width: 80%;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>CONTINENTAL CAFE CUSINE</h1>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="menu.html">MENU</a></li>
                <li><a href="about.html">ABOUT</a></li>
                <li><a href="administration.html">ADMINISTRATION</a></li>
                <li><a href="contactus.html">CONTACT</a></li>
            </ul>
        </div>
    </header>
    
        <div class="container">
            <h2>WELCOME TO CONTINENTAL CAFE CUSINE</h2>
            <p>"A Taste You'll Remember"</p>
            </section>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2024 ELON MUSK. All Rights Reserved.</p>
        </div>
    </footer> 
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
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styling */
        body {
            font-family: 'Arial', sans-serif;
            background-image: url('background.jpg'); /* Background image URL */
            background-size: cover;
            background-position: center;
            color: white;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Header styling */
        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            color: #fff;
            font-size: 36px;
        }

        ul {
            list-style-type: none;
            padding: 10px 0;
        }

        ul li {
            display: inline;
            margin: 0 15px;
        }

        ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
        }

        ul li a:hover {
            color: #f4a261;
        }

        /* Menu section styling */
        .menu-section {
            text-align: center;
            padding: 50px 20px;
        }

        .menu-section h1 {
            font-size: 36px;
            font-weight: bold;
            color: #f4a261;
        }

        .menu-section1, .menu-section2 {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            padding-top: 20px;
        }

        .menu-section1 div, .menu-section2 div {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            width: 200px;
        }

        .menu-section1 img, .menu-section2 img {
            width: 200px;
            height: 200px;
            border-radius: 10px;
            border: 5px solid #fff;
            transition: transform 0.3s ease;
        }

        .menu-section1 img:hover, .menu-section2 img:hover {
            transform: scale(1.1);
        }

        .menu-section1 h2, .menu-section2 h2 {
            margin-top: 10px;
            font-size: 20px;
            font-weight: bold;
        }

        /* Footer styling */
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px 0;
            text-align: center;
            margin-top: auto;
        }

        footer p {
            color: #fff;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <header id="menu">
        <div class="container">
            <h1 id="menu2">MENU</h1>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="menu.html">MENU</a></li>
                <li><a href="about.html">ABOUT</a></li>
                <li><a href="administration.html">ADMINISTRATION</a></li>
                <li><a href="contactus.html">CONTACT</a></li>
            </ul>
        </div>
    </header>

    <section class="menu-section">
        <h1 id="veg">VEG-ITEMS</h1><br>
        <section class="menu-section1">
            <div>
                <img src="rpitcture1.png" alt="Steak Frites" />
                <h2>STEAK FRITES - 1250Rs</h2>
            </div>

            <div>
                <img src="rpicture2.jpg" alt="Chicken Confit" />
                <h2>Chicken Confit - 1500Rs</h2>
            </div>

            <div>
                <img src="rpicture3.jpg" alt="French Onion Soup" />
                <h2>French Onion Soup - 220Rs</h2>
            </div>

            <div>
                <img src="rpicture4.JPG" alt="Bouillabaisse" />
                <h2>Bouillabaisse - 1000Rs</h2>
            </div>

            <div>
                <img src="rpicture5.jpg" alt="Croque Monsieur" />
                <h2>Croque Monsieur - 1220Rs</h2>
            </div>

            <div>
                <img src="rpicture6.jpg" alt="Lamb Shank Navarin" />
                <h2>Lamb Shank Navarin - 1550Rs</h2>
            </div>

            <div>
                <img src="rpicture7.JPG" alt="Hazelnut Dacquoise" />
                <h2>Hazelnut Dacquoise - 800Rs</h2>
            </div>
        </section>

        <h1 id="nonveg">NON-VEG ITEMS</h1><br>
        <section class="menu-section2">
            <div>
                <img src="rpictire8.jpg" alt="Smorrebrod" />
                <h2>Smorrebrod - 2220Rs</h2>
            </div>
        </section>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 ELON MUSK. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>



administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ADMINISTRATION</title>
    <link rel="stylesheet" href="menu.css" type="text/css">
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body styling */
        body {
            font-family: 'Arial', sans-serif;
            background-image: url('background.jpg'); /* Background image URL */
            background-size: cover;
            background-position: center;
            color: white;
            height: 100vh;
            display: flex;
            flex-direction: column;
        }

        /* Header styling */
        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            color: #fff;
            font-size: 36px;
        }

        ul {
            list-style-type: none;
            padding: 10px 0;
        }

        ul li {
            display: inline;
            margin: 0 15px;
        }

        ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
        }

        ul li a:hover {
            color: #f4a261;
        }

        /* Admin section styling */
        .admin-section {
            text-align: center;
            padding: 50px 20px;
        }

        .admin-section1 {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            padding-top: 20px;
        }

        .admin-section1 div {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            width: 200px;
        }

        .admin-section1 img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            border: 5px solid #fff;
            transition: transform 0.3s ease;
        }

        .admin-section1 img:hover {
            transform: scale(1.1);
        }

        .admin-section1 h2 {
            margin-top: 10px;
            font-size: 20px;
            font-weight: bold;
        }

        .admin-section1 p {
            font-size: 16px;
            color: #f4a261;
        }

        /* Footer styling */
        footer {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px 0;
            text-align: center;
            margin-top: auto;
        }

        footer p {
            color: #fff;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>ADMINS</h1>
            <ul>
                <li><a href="home.html">HOME</a></li>
                <li><a href="menu.html">MENU</a></li>
                <li><a href="about.html">ABOUT</a></li>
                <li><a href="administration.html">ADMINISTRATION</a></li>
                <li><a href="contact us.html">CONTACT</a></li>
            </ul>
        </div>
    </header>

    <section class="admin-section">
        <h1 id="chef">CHEFS</h1>
        <section class="admin-section1">
            <div>
                <img src="CEO.jpg" alt="Lokeshwaran R" />
                <h2>LOKESHWARAN.R</h2>
                <p>CEO</p>
            </div>

            <div>
                <img src="http://www.michaeldeane.co.uk/resources/images/dcms/1123/Danni.jpg" alt="Danni Barry" />
                <h2>DANNI BARRY</h2>
                <p>Head Chef</p>
            </div>

            <div>
                <img src="https://tse4.mm.bing.net/th?id=OIP.PBKOa1jU0DMXo7GB_YgA4wHaD8&pid=Api&P=0&h=180" alt="Emma Bengtsson" />
                <h2>EMMA BENGTSSON</h2>
                <p>Head Chef</p>
            </div>

            <div>
                <img src="https://tse2.mm.bing.net/th?id=OIP.a4gVeRbp5AIYda1edHAVugHaE8&pid=Api&P=0&h=180" alt="Eric Pras" />
                <h2>ERIC PRAS</h2>
                <p>Sous Chef</p>
            </div>

            <div>
                <img src="https://tse4.mm.bing.net/th?id=OIP.KEd7vsPiLVCUvZGwbGnY0gHaGq&pid=Api&P=0&h=180" alt="Gordan Ramsay" />
                <h2>GORDAN RAMSY</h2>
                <p>Executive Chef</p>
            </div>

            <div>
                <img src="https://tse2.mm.bing.net/th?id=OIP.qTUNQguXkhSyhND4vAfsbAHaEF&pid=Api&P=0&h=180" alt="Nadia Santini" />
                <h2>NADIA SANTINI</h2>
                <p>Sous Chef</p>
            </div>
        </section>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 ELON MUSK . All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>


about.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ABOUT | CONTINENTAL CAFE CUSINE</title>
    <style>
        /* General Body Styling */
        body {
            font-family: 'Arial', sans-serif;
            background: url('je.webp') no-repeat center center/cover;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Header Styling */
        header {}

        {
            height: 100vh;  
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            position:  relative;
        }

        header h1 {
            font-size: 3em;
            font-weight: bold;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6);
        }

        header ul {
            list-style-type: none;
            padding: 0;
        }

        header ul li {
            display: inline;
            margin-right: 20px;
        }

        header ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: color 0.3s;
        }

        header ul li a:hover {
            color: #ff6347;
        }

        /* About Section Styling */
        .about-section {
            background:pink;
            padding: 50px 20px;
            text-align: center;
        }

        .about-section p {
            font-size: 1.2em;
            color: #555;
            line-height: 1.6;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        .about-section b {
            color: #ff6347;
        }

        /* Footer Styling */
        footer {
            background-color: #333;
            color:chartreuse;
            padding: 20px;
            text-align: center;
        }

        /* Container for centering content */
        .container {
            width: 80%;
            margin: 0 auto;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            .about-section p {
                font-size: 1em;
                padding: 0 20px;
            }
        }
    </style>
</head>
<body>


    <section class="about-section">
        <p id="ABOUT1">
            Welcome to <b>CONTINENTAL CAFE CUSINE</b>!<br><br>
            <strong>Our Beginnings</strong><br>
            In the heart of <b>Chennai</b>, a culinary adventure began in <b>2003</b> with the birth of <b>Continental Cafe Cusine</b>. Founded by a group of passionate food enthusiasts, our journey is a testament to the belief that every meal should be a celebration, a moment to savor and remember.<br><br>

            <strong>The Essence of Flavor</strong><br>
            At <b>CONTINENTAL CAFE CUSINE</b>, we don’t just serve food; we craft experiences. Headed by Executive Chef <b>GORDON RAMSEY</b>, our kitchen is a laboratory of creativity where flavors are explored, combined, and transformed into culinary masterpieces. Each dish on our menu is a reflection of our commitment to pushing the boundaries of taste.<br><br>

            <strong>Our Guiding Principles</strong><br>
            <ul style="list-style-type: none; padding: 0; color: #333;">
                <li>&#10004; Genuine Hospitality</li>
                <li>&#10004; Customer Service Excellence</li>
                <li>&#10004; Quality Food and Beverage</li>
                <li>&#10004; Hygiene and Cleanliness</li>
                <li>&#10004; Efficient Operations</li>
                <li>&#10004; Financial Management</li>
                <li>&#10004; Employee Well-being and Training</li>
                <li>&#10004; Marketing and Branding</li>
                <li>&#10004; Sustainability and Environmental Responsibility</li>
                <li>&#10004; Legal Compliance</li>
                <li>&#10004; Adaptability</li>
            </ul>
        </p>  
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 ELON MUSK. All Rights Reserved.</p>
        </div>
    </footer> 
</body>
</html>


contact.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            margin: 0;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        .contact-info {
            text-align: center;
            margin-bottom: 40px;
        }

        .contact-info h2 {
            font-size: 24px;
            color: #333;
        }

        .contact-info p {
            font-size: 18px;
            color: #555;
        }

        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
        }

        form input,
        form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        form button {
            padding: 10px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <header>
        <h1>Contact Us</h1>
    </header>

    <div class="container">
        <section class="contact-info">
            <h2>Get in Touch</h2>
            <p>We'd love to hear from you! If you have any questions, feedback, or just want to say hello, feel free to reach out.</p>
            <p><strong>Address:</strong> 123 Restaurant Street, Food City</p>
            <p><strong>Phone:</strong> (123) 456-7890</p>
            <p><strong>Email:</strong> info@restaurant.com</p>
        </section>

        <section>
            <form action="#" method="post">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message:</label>
                <textarea id="message" name="message" rows="5" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

</body>
</html>

```
## OUTPUT:

![alt text](<Screenshot (93).png>) 
![alt text](<Screenshot (94).png>) 
![alt text](<Screenshot (95).png>) 
![alt text](<Screenshot (96).png>) 
![alt text](<Screenshot (97).png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
