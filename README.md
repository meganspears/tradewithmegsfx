# tradewithmegsfx
/* General Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  background-color: #1e1e1e;
  color: #fff;
  line-height: 1.6;
}

a {
  text-decoration: none;
  color: inherit;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

h2 {
  text-align: center;
  color: #f3c72e;
  margin-bottom: 30px;
}

/* Navbar Styles */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 5%;
  position: relative;
  z-index: 10;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #f3c72e;
}

.navbar ul {
  list-style: none;
  display: flex;
  gap: 25px;
}

.navbar ul li a {
  color: #fff;
  font-weight: 500;
}

/* Hero Section */
.hero {
  position: relative;
  background: url('https://via.placeholder.com/1920x1080?text=Forex+Trading') no-repeat center center/cover;
  height: 100vh;
  color: white;
  text-align: center;
}

.hero .overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.6);
}

.hero-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.hero-content h1 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero-content p {
  font-size: 20px;
}

.btn {
  background-color: #f3c72e;
  color: white;
  padding: 12px 25px;
  border-radius: 5px;
  font-weight: bold;
  display: inline-block;
  margin-top: 25px;
  transition: background 0.3s ease;
}

.btn:hover {
  background-color: #f3a63b;
}

/* About Section */
.about {
  display: flex;
  flex-wrap: wrap;
  padding: 60px 0;
  align-items: center;
}

.about .text, .about .image {
  flex: 1;
  padding: 20px;
}

.about img {
  width: 100%;
  border-radius: 10px;
}

/* Services Section */
.services {
  background-color: #2b2b2b;
  padding: 60px 0;
}

.service-list {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: space-around;
}

.service-item {
  flex: 1;
  min-width: 250px;
  background: #333;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  text-align: center;
}

.service-item h3 {
  color: #f3c72e;
}

.service-item p {
  color: #ddd;
}

/* Live Trading Chart */
.live-chart {
  padding: 60px 0;
}

.chart-container {
  max-width: 1000px;
  margin: auto;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Testimonials Section */
.testimonials {
  background-color: #333;
  padding: 60px 0;
}

.testimonial-list {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: space-around;
}

.testimonial-item {
  flex: 1;
  min-width: 250px;
  background: #444;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
}

.testimonial-item p {
  font-style: italic;
  margin-bottom: 10px;
}

.testimonial-item h4 {
  color: #f3c72e;
}

/* Contact Section */
.contact {
  padding: 60px 0;
  background: #2b2b2b;
}

.contact form {
  max-width: 600px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.contact input,
.contact textarea {
  padding: 15px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.contact button {
  background-color: #f3c72e;
  color: white;
  padding: 12px 25px;
  border-radius: 5px;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

.contact button:hover {
  background-color: #f3a63b;
}

/* Footer Section */
.footer {
  text-align: center;
  background: #222;
  color: #fff;
  padding: 20px;
}

/* General Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Roboto', sans-serif;
  background-color: #1e1e1e;
  color: #fff;
  line-height: 1.6;
}

a {
  text-decoration: none;
  color: inherit;
}

.container {
  width: 90%;
  max-width: 1200px;
  margin: auto;
}

h2 {
  text-align: center;
  color: #f3c72e;
  margin-bottom: 30px;
}

/* Navbar Styles */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 5%;
  position: relative;
  z-index: 10;
}

.logo {
  font-size: 24px;
  font-weight: bold;
  color: #f3c72e;
}

.navbar ul {
  list-style: none;
  display: flex;
  gap: 25px;
}

.navbar ul li a {
  color: #fff;
  font-weight: 500;
}

/* Hero Section */
.hero {
  position: relative;
  background: url('https://via.placeholder.com/1920x1080?text=Forex+Trading') no-repeat center center/cover;
  height: 100vh;
  color: white;
  text-align: center;
}

.hero .overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.6);
}

.hero-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.hero-content h1 {
  font-size: 48px;
  margin-bottom: 20px;
}

.hero-content p {
  font-size: 20px;
}

.btn {
  background-color: #f3a63b; /* More pink */
  color: white;
  padding: 12px 25px;
  border-radius: 5px;
  font-weight: bold;
  display: inline-block;
  margin-top: 25px;
  transition: background 0.3s ease;
}

.btn:hover {
  background-color: #ff4d77; /* Pink hover */
}

/* About Section */
.about {
  display: flex;
  flex-wrap: wrap;
  padding: 60px 0;
  align-items: center;
}

.about .text, .about .image {
  flex: 1;
  padding: 20px;
}

.about img {
  width: 100%;
  border-radius: 10px;
}

/* Services Section */
.services {
  background-color: #2b2b2b;
  padding: 60px 0;
}

.service-list {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: space-around;
}

.service-item {
  flex: 1;
  min-width: 250px;
  background: #333;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  text-align: center;
}

.service-item h3 {
  color: #f3a63b;
}

.service-item p {
  color: #ddd;
}

/* Live Trading Chart */
.live-chart {
  padding: 60px 0;
}

.chart-container {
  max-width: 1000px;
  margin: auto;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

/* Testimonials Section */
.testimonials {
  background-color: #333;
  padding: 60px 0;
}

.testimonial-list {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  justify-content: space-around;
}

.testimonial-item {
  flex: 1;
  min-width: 250px;
  background: #444;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
}

.testimonial-item p {
  font-style: italic;
  margin-bottom: 10px;
}

.testimonial-item h4 {
  color: #f3a63b;
}

/* Contact Section */
.contact {
  padding: 60px 0;
  background: #2b2b2b;
}

.contact form {
  max-width: 600px;
  margin: auto;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.contact input,
.contact textarea {
  padding: 15px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.contact button {
  background-color: #f3a63b;
  color: white;
  padding: 12px 25px;
  border-radius: 5px;
  font-weight: bold;
  border: none;
  cursor: pointer;
}

.contact button:hover {
  background-color: #ff4d77; /* Pink hover */
}

/* Social Links */
.social-links {
  display: flex;
  justify-content: center;
  gap: 15px;
  margin-top: 30px;
}

.social-icon {
  color: #fff;
  font-size: 24px;
  padding: 10px;
  background-color: #f3a63b; /* Pink */
  border-radius: 50%;
  transition: background 0.3s;
}

.social-icon:hover {
  background-color: #ff4d77; /* Hover Pink */
}

/* Footer Section */
.footer {
  text-align: center;
  background: #222;
  color: #fff;
  padding: 20px;
}
