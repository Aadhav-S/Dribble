# Project Responsive Web Design using Bootstrap
## Date:25/12/2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```

dribble.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribble</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="dribble.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="#">Dribble</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>
    <section id="about" class="content-section bg-light">
        <div class="container text-left">
            <h2>What are you working on?</h2>
            <p class="lead">Dribbble is show and tell for Designers</p>
        </div>
    </section>
    <section id="gallery" class="content-section">
        <div class="container">
            
            <div class="row">
                <div class="col-md-4 mb-4">
                    <img src="nature1.jpg" class="img-fluid gallery-img" alt="Gallery 1">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="nature2.jpg" class="img-fluid gallery-img" alt="Gallery 2">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="nature3.jpg" class="img-fluid gallery-img" alt="Gallery 3">
                </div>
            </div>

            <div class="row">
                <div class="col-md-4 mb-4">
                    <img src="nature4.jpg" class="img-fluid gallery-img" alt="Gallery 1">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="nature5.jpg" class="img-fluid gallery-img" alt="Gallery 2">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="nature6.jpg" class="img-fluid gallery-img" alt="Gallery 3">
                </div>
            </div>

            <div class="text-center mt-4">
                <a href="#" class="btn btn-primary">more</a>
            </div>
        </div>
    </section>
    <section id="contact" class="content-section bg-light">
        <div class="container text-center">
            <h2>Contact Us</h2>
            <p><a href="./contact.html"> Contact us via Email </a></p>
            <a href="mailto:info@example.com" class="btn btn-outline-dark">aadhavselvakumaresan@gmail.com</a>
        </div>
    </section>
    <footer class="footer">
        <div class="container">
            <p>Designed and Developed by Aadhav S</p>
        </div>
    </footer>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.4.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

dribble.css

dy {
    font-family: "Dancing Script", serif;
    font-optical-sizing: auto;
    font-weight: 80%;
    font-style: normal;
}
.navbar {
    background-color: #3d5630;
    padding-top: 30px;
    padding-bottom: 30px;
}
.navbar-brand, .nav-link {
    color: white !important;
}
.content-section {
    padding: 4rem 0;
}
.footer {
    background-color: #3d5630;
    color: white;
    padding: 25px;
    text-align: center;
}
.gallery-img {
    max-height: 430px;
    object-fit: cover;

}
.about {
    max-height: 430px;
    object-fit: cover;
    border-radius: 50px;
}

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Dribble</h1>
        </div>
        <nav>
            <ul>
               
                <li><a href="./contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="page-title">
            <h2>Contact Us</h2>
          
        </section>
        <section class="contact-form">
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" placeholder="Your Name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" placeholder="Your Email" required>
                
              
                
                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>
    <footer>
        <p>Designed and Developed by Aadhav S</p>
    </footer>
</body>
</html>

contact.css

.contact-title {
    text-align: center;
    margin: 30px 0;
    padding: 10px;
    background-color: #fdebd0;
   
    font-size: 2rem;
    font-weight: bold;
    border-radius: 8px;
    
}

/* Contact Form */
.contact-container {
    max-width: 600px;
    margin: 20px auto;
    padding: 20px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    
}

.contact-form label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #333;
}

.contact-form input,
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1rem;
}

.contact-form button {
    background-color: #0b0b0b;
    color: white;
    font-size: 1rem;
    font-weight: bold;
    padding: 10px 15px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    margin: 0 auto;
    display: flex;
    font-family: "Dancing Script", serif;
    font-optical-sizing: auto;
    font-weight: 80%;
    font-style: normal;
}

.contact-form button:hover {
    background-color: #313333;
}

header {
    background-color: #3d5630;
    padding: 10px 20px;
    display: flex;
    color: #ddd;
    justify-content: space-between;
    align-items: center;
    border-bottom: 2px solid #ffffff;
    font-family: "Dancing Script", serif;
    font-optical-sizing: auto;
    font-weight: 80%;
    font-style: normal;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

header h1 {
    font-size: 1.8rem;
    
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
    text-decoration: none;
    color: #ffffff;
    font-size: 1rem;
    font-weight: bold;
    padding: 5px 10px;
    border-radius: 5px;
}

nav ul li a:hover {
    background-color: #ddd;
}

.page-title {
    text-align: center;
    font-family: "Dancing Script", serif;
    font-optical-sizing: auto;
    font-weight: 80%;
    font-style: normal;
}

.page-title div {
    font-size: 22px;
    margin-top: 30px;
    font-weight: bold;
}

main {
    height: 75vh;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #3d5630;
    color: #ffffff;
    margin-top: -10px;
    font-family: "Dancing Script", serif;
    font-optical-sizing: auto;
    font-weight: 80%;
    font-style: normal;
}

footer a {
    text-decoration: none;
    color: #345c46;
    font-weight: bold;
}

footer a:hover {
    text-decoration: underline;
}

.contact-form {
    width: 400px;
    margin: auto;
    margin-top: 100px;
    font-family: "Dancing Script", serif;
    font-optical-sizing: auto;
    font-weight: 80%;
    font-style: normal;
}

.contact-form form button{
    display: flex;
}


```

## OUTPUT:
![alt text](<Screenshot (59).png>)
![alt text](<Screenshot (60).png>)
![alt text](<Screenshot (62).png>)
![alt text](<Screenshot (64).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
