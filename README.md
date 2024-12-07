# Ex.07 Restaurant Website
# Date:
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

# PROGRAM:sudharsan.s(24009664)
     
          ```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Savor & Sizzle</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial Black', Arial, sans-serif; /* Bold font */
            background: linear-gradient(to right, #ff7e5f, #feb47b); /* Gradient background */
            color: #333;
        }
        header {
            background: url('banner.jpg') no-repeat center center/cover;
            height: 400px;
            text-align: center;
            padding: 80px 20px;
            color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        header img {
            width: 150px; /* Adjust the size as needed */
            margin-bottom: 20px;
        }
        nav {
            background-color: #2980b9;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #f1c40f;
        }
        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        #specials {
            background-color: #ffcccc; /* Light red */
        }
        #menu {
            background-color: #ccffcc; /* Light green */
        }
        #administration {
            background-color: #ccccff; /* Light blue */
        }
        #contact {
            background-color: #ffffcc; /* Light yellow */
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #2980b9;
            color: white;
        }
        .specials {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .special {
            width: 30%;
            margin: 20px 0;
            text-align: center;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            background-color: white;
            color: #333;
        }
        .special img {
            width: 100%;
            height: auto;
        }
        .menu-item, .admin-member {
            margin: 15px 0;
            padding: 10px;
            background: #eaeaea;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .admin-member {
            display: inline-block;
            width: 150px;
            margin: 15px;
            text-align: center;
        }
        .admin-member img {
            width: 100px;
            border-radius: 50%;
        }
    </style>
</head>
<body>
    <header>
        <img src="C:\Users\sudharshan\OneDrive\Pictures\Screenshots\Screenshot 2024-10-21 094427.png" alt="Savor & Sizzle Logo"> <!-- Logo Image -->
        <h1>Welcome to Savor & Sizzle</h1>
        <p>Delicious food awaits you! Experience flavors that ignite your palate.</p>
    </header>
    <nav>
        <a href="#specials">Specials</a>
        <a href="#menu">Menu</a>
        <a href="#administration">Our Team</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <section id="specials">
        <h2>Our Specials</h2>
        <div class="specials">
            <div class="special">
                <img src="C:\Users\sudharshan\Downloads\download (1).jpg" alt="Spicy Grilled Salmon">
                <h3>Spicy Grilled Salmon</h3>
                <p>A succulent salmon fillet marinated in spicy herbs.</p>
                <p><strong>Rs 1200</strong></p>
            </div>
            <div class="special">
                <img src="C:\Users\sudharshan\Downloads\download (2).jpg" alt="BBQ Ribs">
                <h3>BBQ Ribs</h3>
                <p>Tender ribs glazed with our secret BBQ sauce.</p>
                <p><strong>Rs 1500</strong></p>
            </div>
            <div class="special">
                <img src="C:\Users\sudharshan\Downloads\download (3).jpg" alt="Garlic Butter Shrimp">
                <h3>Garlic Butter Shrimp</h3>
                <p>Succulent shrimp sautéed in garlic butter and spices.</p>
                <p><strong>Rs 1350</strong></p>
            </div>
        </div>
    </section>

    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">1. Chicken Biryani (SS) - Rs 220</div>
        <div class="menu-item">2. Margherita Pizza - Rs 900</div>
        <div class="menu-item">3. Caesar Salad - Rs 450</div>
        <div class="menu-item">4. Grilled Chicken - Rs 120</div>
        <div class="menu-item">5. Fish and Chips - Rs 100</div>
        <div class="menu-item">6. Tiramisu - Rs 1000</div>
        <div class="menu-item">7. Lasagna - Rs 625</div>
        <div class="menu-item">8. Caprese Salad - Rs 150</div>
        <div class="menu-item">9. Beef Tacos - Rs 720</div>
        <div class="menu-item">10. Vegetable Stir Fry - Rs 360</div>
        <div class="menu-item">11. Shrimp Scampi - Rs 1350</div>
        <div class="menu-item">12. Chocolate Cake - Rs 450</div>
    </section>

    <section id="administration">
        <h2>Meet Our Team</h2>
        <div class="admin-member">
            <img src="C:\Users\sudharshan\Downloads\images (3).jpg" alt="Admin 1"><br>
            <strong>John Doe</strong><br>
            Manager
        </div>
        <div class="admin-member">
            <img src="C:\Users\sudharshan\Downloads\images (4).jpg" alt="Admin 2"><br>
            <strong>Jane Smith</strong><br>
            Head Chef
        </div>
        <div class="admin-member">
            <img src="C:\Users\sudharshan\Downloads\admin 3.jpg" alt="Admin 3"><br>
            <strong>Tom Brown</strong><br>
            Waiter
        </div>
        <div class="admin-member">
            <img src="C:\Users\sudharshan\Downloads\images.jpg" alt="Admin 4"><br>
            <strong>Lucy Green</strong><br>
            Bartender
        </div>
        <div class="admin-member">
            <img src="C:\Users\sudharshan\Downloads\images (1).jpg" alt="Admin 5"><br>
            <strong>Michael White</strong><br>
            Dishwasher
        </div>
        <div class="admin-member">
            <img src="C:\Users\sudharshan\Downloads\images (2).jpg" alt="Admin 6"><br>
            <strong>Sarah Black</strong><br>
            Hostess
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong> 123 Food St, Flavor Town, NY 12345</p>
        <p><strong>Phone:</strong> (123) 456-7890</p>
        <p><strong>Email:</strong> info@savorandsizzle.com</p>
        <p>Follow us on social media for the latest updates!</p>
        <p><strong>Instagram:</strong> @savorandsizzle | <strong>Facebook:</strong> facebook.com/savorandsizzle</p>
    </section>

    <footer>
        <p>© 2024 Savor & Sizzle. All rights reserved.</p>
    </footer>
</body>
</html>
               ```


# OUTPUT:
![Screenshot 2024-11-25 134116](https://github.com/user-attachments/assets/45664c22-1b3f-4e47-8331-a1f583bc63d7)
![Screenshot 2024-11-25 134138](https://github.com/user-attachments/assets/561f1194-5613-4c7b-a7fb-e2c245b6f30f)
![Screenshot 2024-11-25 134155](https://github.com/user-attachments/assets/5471f246-9540-42d6-89ce-703b454e7c86)
![Screenshot 2024-11-25 134251](https://github.com/user-attachments/assets/e0d2149a-eca2-45f2-bb51-014e45f12daf)
![Screenshot 2024-11-25 134310](https://github.com/user-attachments/assets/cf274b3e-9f66-4663-8a35-c9559a44835d)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
