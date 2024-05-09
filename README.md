<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tiger Fit</title>
<style>
  body { font-family: Arial, sans-serif; }
  .navbar { display: flex; justify-content: space-between; align-items: center; padding: 1rem; }
  .logo { border-radius: 50%; }
  .menu { cursor: pointer; }
  .menu-content { display: none; position: absolute; right: 1rem; top: 3rem; background-color: #f9f9f9; box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2); }
  .menu-item { padding: 12px 16px; display: block; }
  .main-content { text-align: center; padding: 2rem; }
  .subscribe { background-color: #f1f1f1; padding: 2rem; text-align: center; }
  .social-icons { display: flex; justify-content: center; }
  .social-icon { margin: 0 10px; }
.search-container {
  width: 100%; 
  padding: 10px;
  background-color: #f0f0f0; /* Adjust background color as desired */
}

.search-container input[type=text] {
  width: calc(100% - 60px); /* Space for button */
  padding: 8px;
  border: 1px solid #ddd;
}

.search-container button {
  background-color: #333; /* Adjust button color */
  color: white;
  padding: 8px;
  border: none;
  cursor: pointer;
}
</style>
</head>
<body>
<div class="search-container">
  <input type="text" placeholder="Search..." name="search">
  <button type="submit"><i class="fa fa-search"></i></button>
</div>

<div class="navbar">
  <img src="tiger.jpg" width=50,height=50 alt="Tiger Fit" class="logo">
  <div class="menu" onclick="toggleMenu()">☰</div>
  <div class="menu-content" id="menuContent">
    <img src="tiger.jpg" width =50,height=50 alt="Tiger Fit " class="logo">
    <a href="#services" class="menu-item">Services</a>
    <a href="#about" class="menu-item">About</a>
    <a href="#contact" class="menu-item">Contact</a>
  </div>
</div>

<div class="main-content">
  <h1>Achieve Your Goals with Tiger Fit</h1>
  <p>Welcome to Tiger Fit, your ultimate online destination for everything related to gym and fitness. Our mission is to help you achieve your fitness goals and lead a healthier life. Our team of experts is dedicated to providing you with the best fitness tips, workouts, and nutrition advice to help you transform your body and lifestyle</p>
  <img src="fitness.jpg" width=900,height=200 alt="Fitness">
</div>
<div>
 <h1>Achieving Fitness Goals: A Personalized Approach</h1>
  <p>Learn how we helped John, a busy entrepreneur, achieve his fitness goals with our personalized approach to personal training, nutrition counseling, and fitness coaching.
*Personalized workout plan
*Customized meal plan
</p>
<img src="f.jpg" width=12, 00,height=200 alt="fitness"align-items:centre>
</div>
<div class="approach">
  <!-- Add your content about the approach to fitness goals here -->
</div>

<div class="community">
  <!-- Add your content about building a healthier community here -->
</div>

<div class="subscribe">
  <h2>Subscribe to Newsletter</h2>
  <input type="email" placeholder="Enter your email address">
  <button>Register</button>
</div>

<div class="social-icons">
  <a href="https://instagram.com" class="social-icon">Instagram</a>
  <a href="https://twitter.com" class="social-icon">Twitter</a>
  <a href="mailto:info@tigerfit.com" class="social-icon">Email</a>
</div>

<script>
function toggleMenu() {
  var menuContent = document.getElementById("menuContent");
  if (menuContent.style.display === "block") {
    menuContent.style.display = "none";
  } else {
    menuContent.style.display = "block";
  }
}
</script>

</body>
</html>
