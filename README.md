# Project: Responsive Web Design using Bootstrap
# Date:13.05.2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel World</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body class="bg-light">
  
    
    <nav class="navbar navbar-expand-lg bg-dark fixed-top border-bottom border-body" data-bs-theme="dark">
        <div class="container-fluid">
            <a class="navbar-brand text-white" href="#">Trip Trastic</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item">
                        <a class="nav-link active text-white" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active text-white" href="#explore">Explore</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active text-white" href="#contact">Contact</a>
                    </li>
                </ul>
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                    <button class="btn btn-outline-success" type="submit">Search</button>
                </form>
            </div>
        </div>
    </nav>

   
    <div id="carouselExampleFade" class="carousel slide carousel-fade mt-5" data-bs-ride="carousel">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleFade" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleFade" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleFade" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="wonder 6.avif" class="d-block w-100" alt="Tamil Nadu">
                <div class="carousel-caption">
                    <h3>ASPECTS OF NATURE</h3>
                    <p>Explore the nature, admiring it!</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="wonder 1.jpg" class="d-block w-100" alt="Waterfalls">
                <div class="carousel-caption">
                    <p>The beauty of the sound of falls!</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="wonder3.jpg" class="d-block w-100" alt="Nature">
                <div class="carousel-caption">
                    <p>The nature's music, the calmness inherited!</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleFade" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
        </button>
    </div>

    
    <div id="explore" class="my-5">
        <h1 class="text-center">DISCOVER THE GEMS OF TAMILNADU</h1>
        <div class="container mt-4">
            <div class="row">
                <div class="col-md-4">
                    <div class="card h-100">
                        <img src="wonder 5.jpg" class="card-img-top" alt="Coorg">
                        <div class="card-body">
                            <h5 class="card-title">METTUR</h5>
                            <p class="card-text">Mettur is an industrial and tourist town located in the Salem district in the state of Tamil Nadu, India. It is best known for the Mettur Dam which is the largest dam in south India.</p>
                            <a href="#" class="btn btn-primary">Explore</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100">
                        <img src="wonder 1.jpg" class="card-img-top" alt="VALPARAI">
                        <div class="card-body">
                            <h5 class="card-title">VALPARAI</h5>
                            <p class="card-text">Valparai is a hill station in the Coimbatore district of Tamil Nadu, India, known for its tea estates, forests, and mountains.</p>
                            <a href="#" class="btn btn-primary">Explore</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100">
                        <img src="wonder 3.jpg" class="card-img-top" alt="KODAIKANAL">
                        <div class="card-body">
                            <h5 class="card-title">KODAIKANAL</h5>
                            <p class="card-text">Kodaikanal is a hill station town in Tamil Nadu, India, known for its scenic beauty, cool weather, and many things to do</p>
                            <a href="#" class="btn btn-primary">Explore</a>
                        </div>
                       
                    </div>
                </div>
            </div>
        </div>
    </div>

   
    <div id="contact" class="my-5">
        <h1 class="text-center">Contact Us</h1>
        <p class="text-center">To travel many places and enjoy more, contact us with your query.</p>
        <div class="container">
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Enter your name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email Address</label>
                    <input type="email" class="form-control" id="email" placeholder="name@example.com">
                </div>
                <div class="mb-3">
                    <label for="query" class="form-label">Your Query</label>
                    <textarea class="form-control" id="query" rows="3" placeholder="Write your query here"></textarea>
                </div>
                <button type="submit" class="btn btn-danger">Send Query</button>
            </form>
        </div>
    </div>

    
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed by, Rishivarman R</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-rkN0JAy1oF80hZvMxFEWzMa2Xkfwk1Y3YvNoobxD1iTF66iQzlH2jOtZSmU8M1mC" crossorigin="anonymous"></script>
</body>
</html>

```
# OUTPUT:
![project](https://github.com/user-attachments/assets/84ae36f8-72fc-4ba5-a5b6-5d7a5ee72035)

![project 2](https://github.com/user-attachments/assets/1ec95290-07e6-4616-bafd-5093487e3cc7)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
