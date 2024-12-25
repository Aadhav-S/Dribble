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
html code

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
            <p>Contact us via Email</p>
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

css code

body {
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

```

## OUTPUT:
![alt text](<Screenshot (56).png>)
![alt text](<Screenshot (58).png>)
![alt text](<Screenshot (57).png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
