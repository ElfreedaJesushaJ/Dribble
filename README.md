# Project Responsive Web Design using Bootstrap
## Date:31.12.2024

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
game.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Discover</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Sign Up</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Log In</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    
    <header class="bg-dark text-white text-center py-5">
        <div class="container">
            <h1 class="display-4">Showcase Your Design Talent</h1>
            <p class="lead">Join a community of designers and share your work with the world.</p>
            <a href="#" class="btn btn-primary btn-lg">Get Started</a>
        </div>
    </header>

   
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-4">Featured Shots</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="d1.png" class="card-img-top" alt="Shot 1">
                        <div class="card-body">
                            <h5 class="card-title">Design 1</h5>
                            <p class="card-text">A description of the design.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="d2.png" class="card-img-top" alt="Shot 2">
                        <div class="card-body">
                            <h5 class="card-title">Design 2</h5>
                            <p class="card-text">A description of the design.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="d3.png" class="card-img-top" alt="Shot 3">
                        <div class="card-body">
                            <h5 class="card-title">Design 3</h5>
                            <p class="card-text">A description of the design.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

  
    <section class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">What Designers Are Saying</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <div class="card-body">
                            <p class="card-text">"Dribbble has been a great platform to showcase my work and get feedback from other designers."</p>
                            <footer class="blockquote-footer">John Doe, Graphic Designer</footer>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <div class="card-body">
                            <p class="card-text">"The community is so supportive and full of talented creatives. It's my go-to platform!"</p>
                            <footer class="blockquote-footer">Jane Smith, UX Designer</footer>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <div class="card-body">
                            <p class="card-text">"I've connected with so many designers and clients through Dribbble. Highly recommend!"</p>
                            <footer class="blockquote-footer">Samuel Lee, Web Developer</footer>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <footer class="bg-dark text-white text-center py-4">
        <p>&copy; 2024 Elfreeda Jesusha J 24900146. All Rights Reserved.</p>
    </footer>


    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
</body>

</html>

```


## OUTPUT:

![alt text](<ex 10 op.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
