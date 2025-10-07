# Ex.07 Restaurant Website
## Date:7.10.25
## Name:Balaji B M
## Ref No:25016669

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - CUDDALORE DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<style class="css">
    /* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
  </style>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <section class="admin-grid">
    <div class="admin-card">
      <img src="saudh.jpg" alt="MOHAMED SAUDH">
      <h3>MOHAMED SAUDH</h3>
      <p>Manager</p>
    </div>

    <div class="admin-card">
      <img src="mani.jpg" alt="MANIKANDAN">
      <h3>MANIKANDAN</h3>
      <p>Head Chef</p>
    </div>

    <div class="admin-card">
      <img src="mohan.jpg" alt="MOHAN RAJI">
      <h3>MOHAN RAJI</h3>
      <p>Head Chef</p>
    </div>

    <div class="admin-card">
      <img src="sanjay.jpg" alt="SANJAY">
      <h3>SANJAY</h3>
      <p>Assistant Chef</p>
    </div>

    <div class="admin-card">
      <img src="naveen.jpg" alt="NAVEENKUMAR">
      <h3>NAVEENKUMAR</h3>
      <p>Assistant Chef</p>
    </div>

    <div class="admin-card">
      <img src="hariprasath.jpg" alt="HARI PRASATH">
      <h3>HARI PRASATH</h3>
      <p>Cashier</p>
    </div>

    <div class="admin-card">
      <img src="me.jpg" alt="BALAJI B M">
      <h3>BALAJI B M</h3>
      <p>Inventory Manager</p>
    </div>

    <div class="admin-card">
      <img src="vicky.jpg" alt="VIGNESHWAREN">
      <h3>VIGNESHWAREN</h3>
      <p>Customer Service</p>
    </div>
  </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - CUDDALORE DABHA</title>
  <link rel="stylesheet" href="style.css">
  <style class="css">
    /* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
  </style>
</head>
<body>
  <header>
    <h1> CUDDALORE DABHA</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <section class="banner">
    <img src="hotel.png" "Delicious Food Banner">
  </section>



  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  

  <footer>
    <p>&copy; 2025. Designed by BALAJI B M</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - CUDDALORE DABHA</title>
  <link rel="stylesheet" href="style.css">
  <style class="css">
    /* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
  </style>
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 123 WEST Street, ANNA NAGAR, CUDDALORE, TAMIL NADU-610601</p>
    <p>📞 <strong>Phone:</strong> (999)) 123-456-7890 </p>
    <p>✉ <strong>Email:</strong> cuddaloredabha@gmail.com</p>
  </section>
  


 <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by BALAJI B M</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - CUDDALORE DABHA</title>
  <link rel="stylesheet" href="style.css">
  <style class="css">
    /* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}
  </style>
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 09 items -->
    <div class="menu-item">
      <img src="9.jpeg" alt="shavarma">
      <h3>Shavarma</h3>
      <p>Shavarma with the taste of Arabia</p>
    </div>
    <div class="menu-item">
      <img src="7.jpg" alt="Parota with Beef Curry">
      <h3>Parota&Beef</h3>
      <p>Parota&Beef with vegies.</p>
    </div>
    <div class="menu-item">
      <img src="12.jpeg" alt="Mac & Cheese">
      <h3>Creamy Cheese</h3>
      <p>Sooo Cheese.. with bacon.</p>
    </div>
    <div class="menu-item">
      <img src="11.jpeg" alt="Brownie">
      <h3>Choco Brownie</h3>
      <p>Spoongy Brownie which melts in your mouth</p>
    </div>
    <div class="menu-item">
      <img src="3.jpg" alt="Payasam">
      <h3>Creamy Payasam</h3>
      <p>Sweetness with the taste of Payasam.</p>
    </div>
    <div class="menu-item">
      <img src="2.jpg" alt="Lobster">
      <h3>Hot Lobster</h3>
      <p>Juicy Lobster with soft bun</p>
    </div>
    <div class="menu-item">
      <img src="10.jpeg" alt="Prawn">
      <h3>GRILLED PRAWN</h3>
      <p>Juicy prawn with garlic Flavour.</p>
    </div>
    <div class="menu-item">
      <img src="8.jpg" alt="Coke">
      <h3>Zero Sugar Coke</h3>
      <p>Cold and Refreshing Coke.</p>
    </div>
    <div class="menu-item">
      <img src="5.jpg" alt="Crab">
      <h3>Smoked Crab</h3>
      <p>Green coloured spicy Crab.</p>
    </div>
    <div class="menu-item">
      <img src="1.jpg" alt="Pancakes">
      <h3>Pancakes</h3>
      <p>Fluffy pancakes with syrup.</p>
    </div>
    <div class="menu-item">
      <img src="4.jpg" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops.</p>
    </div>
    <div class="menu-item">
      <img src="6.jpg" alt="Fries">
      <h3>French Fries</h3>
      <p>Crispy golden fries.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by BALAJI B M</p>
  </footer>
</body>
</html>
```

## OUTPUT:

<img width="1920" height="1020" alt="Screenshot 2025-10-07 230716" src="https://github.com/user-attachments/assets/8f9208d5-ad2c-4a88-b048-e746f892124a" />
<img width="1920" height="1020" alt="Screenshot 2025-10-07 230742" src="https://github.com/user-attachments/assets/bf197eb9-ced0-4a45-aa02-4be857e3c7a5" />
<img width="1920" height="1020" alt="Screenshot 2025-10-07 230809" src="https://github.com/user-attachments/assets/a8934a35-de3e-4f8a-b37e-f578d365c0e2" />
<img width="1920" height="1020" alt="Screenshot 2025-10-07 230824" src="https://github.com/user-attachments/assets/829b8632-0bf8-454c-b3de-3aa18506d5b2" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
