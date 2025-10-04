# Ex.07 Restaurant Website
## Date:5/10/2025

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dosai kadai</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    <header>
        <nav>
            <ul class="nav-links">
                <li><a href="#" class="active">HOME</a></li>
                <li><a href="#">MENU</a></li>
                <li><a href="#">ADMIN</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <div class="overlay">
                <h1>Rich. Exquisite. Delightful.</h1>
                <p class="tagline">A taste of tradition in every bite — where the flavors of india come alive.</p>
                <p class="invite">
                    Welcome to Dosai kadai, where passion meets the plate.
                    We serve handcrafted dishes made from the freshest local ingredients.
                    Whether you're here for a quick bite or a special celebration,
                    our warm atmosphere and attentive service await.
                    Come hungry, leave happy — that’s our promise to you.
                </p>
            </div>
        </section>      
        <p class="copyright">&copy; 25011340 Krithik kiran.S</p>


    </main>
</body>
</html>
menu.html

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Our Menu</title>
  <link rel="stylesheet" href="style2.css" />
</head>
<body>
  <header>
    <nav>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Menu</a></li>
        <li><a href="#">Administration</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </nav>
    <h1>Our Menu</h1>
  </header>

  <main class="menu-grid">

    <div class="menu-item">
      <img src="Screenshot 2025-10-04 205553.png" alt="Plain dosa" />
      <h2>Plain dosa</h2>
      <p>₹50</p>
    </div>
    <div class="menu-item">
      <img src="ghee.png" alt="Ghee dosa" />
      <h2>Ghee dosa</h2>
      <p>₹65</p>
    </div>
    <div class="menu-item">
      <img src="onion.png" alt="Onion dosa" />
      <h2>Onion dosa</h2>
      <p>₹65</p>
    </div>
    <div class="menu-item">
      <img src="panner.png" alt="Panner dosa" />
      <h2>Panner dosa </h2>
      <p>₹80</p>
    </div>
    <div class="menu-item">
      <img src="pizza.png" alt="Pizza dosa" />
      <h2>Pizza dosa</h2>
      <p>₹90</p>
    </div>
    <div class="menu-item">
      <img src="masala.png" alt="Masala dosa" />
      <h2>Masala dosa</h2>
      <p>₹75</p>
    </div>
    <div class="menu-item">
      <img src="podi.png" alt="Podi dosa" />
      <h2>Podi dosa</h2>
      <p>₹55</p>
    </div>
        <div class="menu-item">
      <img src="rava.png" alt="Rava dosa" />
      <h2>Rava dosa</h2>
      <p>₹70</p>
    </div>
        <div class="menu-item">
      <img src="onion rava.png" alt=" Onion Rava dosa" />
      <h2>Onion Rava dosa</h2>
      <p>₹90</p>
    </div>
        <div class="menu-item">
      <img src="kal.png" alt="Kal dosa" />
      <h2>Kal dosa</h2>
      <p>₹75</p>
    </div>
  </main>
          <p class="copyright">&copy; 25011340 Krithik kiran.S</p>
</body>
</html>

owner.html


<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Administration Team</title>
  <link rel="stylesheet" href="style3.css" />
</head>
<body>
  <header>
    <h1>Administration Team</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Menu</a></li>
        <li><a href="#">Administration</a></li>
        <li><a href="#">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <h2>Meet Our Team</h2>
    <section class="team-grid">
      <div class="team-card">
        <img src="rdj.png" alt="rdj" />
        <h3>RDJ</h3>
        <p>CEO</p>
      </div>
      <div class="team-card">
        <img src="tom cruise.png" alt="Tom cruise" />
        <h3>Tom cruise</h3>
        <p>Marketing Manager</p>
      </div>
      <div class="team-card">
        <img src="tom holland.png" alt="Tom Holland" />
        <h3>Tom Holland</h3>
        <p>Operations Manager</p>
      </div>
      <div class="team-card">
        <img src="rogers.png" alt="Rogers" />
        <h3>Rogers</h3>
        <p>HR Manager</p>
      </div>
      <div class="team-card">
        <img src="steve.png" alt="Steve" />
        <h3>Steve</h3>
        <p>Executive Chef</p>
      </div>
      <div class="team-card">
        <img src="hardy.png" alt="Hardy" />
        <h3>Hardy</h3>
        <p>Customer Service Manager</p>
      </div>
    </section>
  </main>

  <footer>
    <p>© (25011340) Krithik kiran.S</p>
  </footer>
</body>
</html>

visit.html

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Red Dragon Contact</title>
  <link rel="stylesheet" href="style4.css" />
</head>
<body>
  <div class="background">
    <div class="overlay">
      <h2>Contact Us</h2>
      <p><strong>Visit us at:</strong><br>no 8992 TNHB Ayapakkam chennai-77, India</p>
      <p><strong>Phone:</strong> 9962507989</p>
      <p><strong>Email:</strong> <a href="arumugam06032008@gmail.com">arumugam06032008@gmail.com</a></p>
    </div>
  </div>
</body>
</html>

style1.css


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', sans-serif;
    color: white;
    background-image: url('bg.png'); 
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}

header {
    background-color: black;
    padding: 1rem 2rem;
}

.nav-links {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.nav-links a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    padding: 0.5rem 1rem;
    transition: background 0.3s ease;
}

.nav-links a:hover,
.nav-links .active {
    background-color: red;
    border-radius: 5px;
}

.hero {
    height: 80vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 2rem;
    background-color: rgba(0, 0, 0, 0.167);
}

.overlay {
    max-width: 800px;
    background-color: rgba(0, 0, 0, 0.616);
    padding: 2rem;
    border-radius: 10px;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: yellow;
}

.tagline {
    font-size: 1.2rem;
    margin-bottom: 1rem;
    font-style: italic;
}

.invite {
    font-size: 1rem;
    line-height: 1.6;
}

.interior {
    padding: 2rem;
    text-align: center;
}

.interior img {
    max-width: 90%;
    border-radius: 10px;
}


.copyright {
  text-align: center;
  font-size: 16px;
  color: white;
  margin-top: 20px;
}

style2.css


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fff8e1;
  color: #333;
}
header {
  background-color: #ffcc00;
  padding: 20px;
  text-align: center;
  border-bottom: 5px solid #d32f2f;
}

nav {
  margin-bottom: 10px;
}

.nav-links {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 30px;
}

.nav-links a {
  text-decoration: none;
  color: #d32f2f;
  font-weight: bold;
  font-size: 1.1em;
}

h1 {
  font-size: 2.5em;
  color: #d32f2f;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 30px;
}

.menu-item {
  background-color: #fff;
  border: 2px solid #ffcc00;
  border-radius: 10px;
  padding: 15px;
  text-align: center;
  transition: transform 0.2s ease;
}

.menu-item:hover {
  transform: scale(1.05);
}

.menu-item img {
  width: 80%;
  height: 90px;
  object-fit: cover;
  border-radius: 8px;
}

.menu-item h2 {
  margin: 10px 0 5px;
  color: #d32f2f;
}

.menu-item p {
  font-size: 1.1em;
  color: #333;
}

.copyright {
  text-align: center;
  font-size: 16px;
  color: black;
  margin-top: 20px;
}

style3.css


* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-image: url('bg.png'); 
  color: white;
}

header {
  background: linear-gradient(to right, #f39c12, #e74c3c);
  padding: 20px;
  text-align: center;
  color: white;
}

header h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 30px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

main {
  padding: 40px 20px;
  text-align: center;
}

main h2 {
  font-size: 2em;
  margin-bottom: 30px;
}

.team-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 30px;
  justify-items: center;
}

.team-card {
  background-color: #000;
  border: 3px solid orange;
  color: white;
  padding: 20px;
  width: 220px;
  border-radius: 10px;
  text-align: center;
}

.team-card img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  margin-bottom: 15px;
}

.team-card h3 {
  font-size: 1.2em;
  margin-bottom: 5px;
}

.team-card p {
  font-size: 1em;
  color: #f39c12;
}

/* Footer */
footer {
  background-color: #222;
  color: #ccc;
  text-align: center;
  padding: 15px;
  font-size: 0.9em;
}
style4.css

/* Reset and base styles */
body, html {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', sans-serif;
  height: 100%;
}

/* Background image and layout */
.background {
  background-image: url('lanterns.jpg'); /* Replace with actual lantern image path */
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

/* Pink overlay styling */
.overlay {
  background-color: rgba(255, 192, 203, 0.9); /* Soft pink with transparency */
  padding: 30px 40px;
  border-radius: 12px;
  box-shadow: 0 0 20px rgba(0,0,0,0.3);
  text-align: center;
  max-width: 350px;
}

.overlay h2 {
  margin-top: 0;
  font-size: 24px;
  color: #b30000;
}

.overlay p {
  margin: 10px 0;
  font-size: 16px;
  color: #333;
}

.overlay a {
  color: #b30000;
  text-decoration: none;
}

.overlay a:hover {
  text-decoration: underline;
}
```
## OUTPUT:
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (8).png>)
![alt text](<Screenshot (7).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
