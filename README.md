/* General Styles */
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-color: #f9f9f9;
}

header {
  background-color: #1a1a1a;
  color: white;
  padding: 20px;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav .logo {
  font-size: 28px;
  font-weight: bold;
}

nav ul {
  list-style: none;
  display: flex;
}

nav ul li {
  margin-left: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 16px;
}

/* Hero Section */
.hero {
  background-image: url('hero-bg.jpg');
  background-size: cover;
  background-position: center;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero h1 {
  font-size: 48px;
}

.hero p {
  font-size: 20px;
}

.hero .btn {
  background-color: #f5a623;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

/* Menu Section */
#menu {
  padding: 50px 20px;
  background-color: #fff;
}

.menu-item {
  display: flex;
  align-items: center;
  margin-bottom: 20px;
}

.menu-item img {
  width: 150px;
  margin-right: 20px;
}

.menu-item h3 {
  font-size: 24px;
  margin-bottom: 10px;
}

.menu-item p {
  font-size: 16px;
}

/* Gallery Section */
#gallery {
  padding: 50px 20px;
  background-color: #f0f0f0;
}

.swiper-container {
  width: 100%;
  height: 100%;
}

.swiper-slide img {
  width: 100%;
  height: auto;
}

/* Contact Section */
#contact {
  padding: 50px 20px;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #ddd;
  border-radius: 5px;
}

form button {
  background-color: #1a1a1a;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
}

.social-links {
  margin-top: 20px;
}

.social-links a {
  color: #1a1a1a;
  margin-right: 20px;
  text-decoration: none;
}

/* Footer */
footer {
  background-color: #1a1a1a;
  color: white;
  text-align: center;
  padding: 10px;
}
