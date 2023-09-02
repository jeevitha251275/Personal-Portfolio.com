<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jeevitha - Portfolio</title>
    
    <!-- Bootstrap CSS link -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
<style>
    /* Change the color of the "Get in Touch" button */
    .btn-primary {
        background-color: #4CAF50; /* Green color */
        border-color: #4CAF50; /* Green color */
    }

    /* Change the button text color */
    .btn-primary:hover {
        background-color: #45a049; /* Darker green color on hover */
        border-color: #45a049; /* Darker green color on hover */
    }
</style>

</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Jeevitha</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#education">Education</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#projects">Projects</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <div class="container text-center">
            <h1 class="display-4">Hello, I'm Jeevitha</h1>
            <p class="lead">A Computer Science Engineering Student</p>
            <a href="#contact" class="btn btn-primary btn-lg">Get in Touch</a>
        </div>
    </header>

    <!-- About Section -->
<section id="about" class="py-5">
     <div class="container pl-5 d-flex justify-content-center">
        <div class="row align-items-center">
            <div class="col-lg-6">
                <h2 class="display-4">About Me</h2>
                <p>Dedicated and ambitious CS student, actively seeking an internship
opportunity for my final year. Eager to apply my academic knowledge and
gain practical work experience in a real-world setting. Committed to
contributing effectively to a dynamic team while developing valuable
skills that will shape my future career in the tech industry.</p>
            </div>
            <div class="col-lg-6">
                <div class="col-lg-6">
                    <img src="C:\Users\jeevi\OneDrive\Desktop\picture.jpg" class="img-fluid rounded-circle" width="150" height="150">
                </div>
            </div>
        </div>
    </div>
</section>


    <!-- Education Section -->
    <section id="education" class="bg-light py-5">
        <div class="container">
            <h2 class="display-4 text-center">Education</h2>
            <div class="row">
                <div class="col-md-6">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">RNSIT - Computer Science Engineering</h5>
                            <p class="card-text">I am presently pursuing a degree in Computer Science Engineering. My
current CGPA 6.8</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">Oxford English High School - 10th Grade</h5>
                            <p class="card-text">Percentage: 79.52%</p>
                        </div>
                    </div>
                    <div class="card mb-4">
                        <div class="card-body">
                            <h5 class="card-title">PVP Polytechnic - Diploma in computer Science</h5>
                            <p class="card-text">I have completed my diploma in Computer Science with a grade of 
Percentage: 85%</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!-- Projects Section -->
<section id="projects" class="py-5">
    <div class="container">
        <h2 class="display-4 text-center">Projects</h2>
        <div class="row">
            <div class="col-lg-6">
                <div class="card mb-4">
                    <div class="card-body">
                        <h5 class="card-title">Portfolio Website</h5>
                        <p class="card-text">Crafted a personal portfolio website showcasing accomplishments and skills.</p>
                        <p class="card-text">Built using HTML, CSS</p>
                    </div>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="card mb-4">
                    <div class="card-body">
                        <h5 class="card-title">Twitter Clone</h5>
                        <p class="card-text">The creation of a Twitter clone website was built by leveraging educational resources from Udemy.</p>
                        <p class="card-text">Built using HTML, CSS, JavaScript, and Node.js.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>


<section id="contact" class="bg-dark text-white py-5">
    <div class="container">
        <h2 class="display-4 text-center text-uppercase text-white mb-5">Get in Touch</h2>
        <div class="row">
            <div class="col-lg-6 mx-auto">
                <p class="lead text-center">Feel free to reach out to me for any inquiries or collaboration opportunities.</p>
                <ul class="list-unstyled contact-info text-center">
                    <li class="mb-4"><i class="fas fa-phone fa-fw mr-2"></i> Phone: +91 9148894477</li>
                    <li class="mb-4"><i class="far fa-envelope fa-fw mr-2"></i> Email: <a href="mailto:jeevithasatish02@gmail.com" class="text-white">jeevithasatish02@gmail.com</a></li>
                </ul>
                <p class="mb-0 text-center">
                    <a href="https://www.linkedin.com/in/jeevitha-s-03aa06209/" class="linkedin-link btn btn-primary" target="_blank">Connect on LinkedIn</a>
                </p>
            </div>
        </div>
    </div>
</section>




    <!-- Footer Section -->
    <footer class="bg-light text-dark py-4">
        <div class="container text-center">
            <p>&copy; 2023 Jeevitha. All rights reserved.</p>
        </div>
    </footer>

    <!-- Bootstrap JS scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
