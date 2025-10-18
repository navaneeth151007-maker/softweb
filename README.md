# Ex.07 Restaurant Website
## Date:10-10-2025

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

admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <h1>Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html" class="active">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Meet Our Team</h2>

        <div class="team">
            <div class="member">
                <img src="me.jpg" alt="Kervin.S">
                <h3>NKK</h3>
                <p>CEO</p>
            </div>

            <div class="member">
                <img src="a2.jpg" alt="Arun">
                <h3>Arun</h3>
                <p>Marketing Manager</p>
            </div>

            <div class="member">
                <img src="a3.jpg" alt="James">
                <h3>James</h3>
                <p>Operations Manager</p>
            </div>

            <div class="member">
                <img src="a4.jpg" alt="Rahul">
                <h3>Rahul</h3>
                <p>HR Manager</p>
            </div>

            <div class="member">
                <img src="a5.jpg" alt="Albert">
                <h3>Albert</h3>
                <p>Executive Chef</p>
            </div>

            <div class="member">
                <img src="a6.jpg" alt="Newton">
                <h3>Newton</h3>
                <p>Customer Service Manager</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 THE SIX TASTES RESTAURANT | Designed by <strong>NKK</strong></p>
    </footer>
</body>
</html>
```
admin.css
```
body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background-color: #fff;
}

/* Header */
header {
  background-color: #FFD500;
  color: red;
  text-align: center;
  padding: 20px 0;
}

header h1 {
  margin: 0;
  font-size: 2em;
  font-weight: bold;
}

nav ul {
  list-style-type: none;
  padding: 0;
  margin: 10px 0 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: black;
  font-weight: 600;
}

nav ul li a.active {
  text-decoration: underline;
}

/* Main Section */
main {
  text-align: center;
  padding: 40px 20px;
}

main h2 {
  color: #222;
  font-size: 1.8em;
  margin-bottom: 40px;
}

/* Team Cards */
.team {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 25px;
}

.member {
  background-color: #111;
  color: white;
  border-radius: 12px;
  width: 150px;
  padding: 20px;
  transition: transform 0.3s;
}

.member:hover {
  transform: translateY(-8px);
}

.member img {
  width: 80%;
  height: 230px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid orange;
}

.member h3 {
  margin-top: 15px;
  color: #fff;
  font-size: 1.2em;
}

.member p {
  color: #FFD500;
  font-weight: 500;
}

/* Footer */
footer {
  background-color: #222;
  color: white;
  text-align: center;
  padding: 10px;
  font-size: 0.9em;
}
```
home.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Six Tastes Restaurant | Home</title>
  <link rel="stylesheet" href="home.css">
</head>
<body>
  <header>
    <h1>THE SIX TASTES RESTAURANT</h1>
    <p class="tagline">"Healthy.Traditional.Delightful."</p>

    <nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    <h2>Welcome to The Six Tastes Restaurant</h2>
    <p>At Six Tastes Restaurant, we celebrate the timeless art of balance — bringing together the six essential tastes that define Indian cuisine: sweet, sour, salty, bitter, pungent, and astringent.</p>
    <img src="ad1.jpg">
  </section>

  <footer>
    <p>© 2025 THE SIX TASTES RESTAURANT | Designed by <strong>NKK</strong></p>
  </footer>
</body>
</html>
```
home.css
```
body {
  background-image: url('home.jpeg');
  font-family: Arial, sans-serif;
  background-color: black;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid red;
}

.tagline {
  position: relative;
  color: #ffcc66;
  font-size: 16px;
  margin-top: 5px;
  font-style: italic;
  letter-spacing: 1px;
  right: 30%;
}

h1 {
  position: relative;
  color: red;
  right: 30%;
  top: 20%;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left: 30%;
}

nav a.active,
nav a:hover {
  color: red;
  position: relative;
  left: 30%;
}

.home {
  padding: 40px;
}

.home img {
  width: 500px;
  border-radius: 10px;
  margin-top: 20px;
  border: 3px solid red;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid red;
}
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu | Six Taste</title>
  <link rel="stylesheet" href="menu.css">
</head>
<body>
  <header>
    <h1>OUR SPECIAL MENU</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Food Items</h2>
    <div class="menu-items">
      <div class="item"><img src="dily.jpg"><p>Idly - Rs.30</p></div>
      <div class="item"><img src="dosa.jpg"><p>Dosa - Rs.80</p></div>
      <div class="item"><img src="pon.jpg"><p>Pongal- Rs.70</p></div>
      <div class="item"><img src="pori.jpg"><p>Poori - Rs.50</p></div>
      <div class="item"><img src="cha.jpg"><p>Chapathi - Rs.60</p></div>
      <div class="item"><img src="paro.jpg"><p>Parotta - Rs.40</p></div>
    </div>
  </section>

  <footer>
    <p>© 2025 THE SIX TASTES RESTAURANT | Designed by <strong>NKK</strong></p>
  </footer>
</body>
</html>
```
menu.css
```
body {
  font-family: Arial, sans-serif;
  background-color: #111;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid red;
}

h1 {
  color: red;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: red;
}

.menu {
  padding: 40px;
}

.menu-items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.item {
  background-color: black;
  border: 2px solid red;
  border-radius: 10px;
  padding: 10px;
  width: 200px;
}

.item img {
  width: 100%;
  border-radius: 8px;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid red;
}
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | The Six Tastes Restaurant</title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>CONTACT US</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  
   
  <section class="contact">
    <h2>Contact Us</h2>
    <p>📍 14 Anna Nagar,Chennai,Tamil Nadu, India</p>
    <p>📞 1234567890</p>
    <p>✉️ abcd@gmail.com</p>
  </section>

  <footer>
    <p>© 2025 The Six Tastes Restaurant | Designed by <strong>NKK</strong></p>
  </footer>
</body>
</html>
```
contact.css
```
body {
  font-family: Arial, sans-serif;
  background-color: black;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid red;
}

h1 {
  color: red;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: red;
}

.contact {
  padding: 50px;
}

footer {
  background-color: #111;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid red;
}
```
## OUTPUT:
<img width="1884" height="880" alt="Screenshot 2025-10-10 112942" src="https://github.com/user-attachments/assets/6e5b48b2-d089-4d83-9f03-d197ba387c7e" />
<img width="1920" height="1080" alt="Screenshot 2025-10-10 112447" src="https://github.com/user-attachments/assets/82f9382a-e891-4b2a-bb74-0acb21c21e56" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b496c386-3dae-46b8-b82d-1d3d4aec2c9d" />
<img width="1920" height="1020" alt="Screenshot 2025-10-10 112506" src="https://github.com/user-attachments/assets/b908358c-9c11-4883-8954-403e7fdf40ae" />





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
