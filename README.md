# Project Responsive Web Design using Bootstrap
## Date: 18-11-2025
## Reg no: 212224230256
## Name : Sathish kumar .M

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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
    body {
        background-image: url("clothbg11.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-attachment: fixed;
        background-position: center;
    }
</style>


</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">

       <div class="container">
            <a class="navbar-brand" href="#">Bubblevolume</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#">Explore</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Suggestions</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Updates</a></li>
                    <li class="nav-item"><a class="nav-link" href="#">Blog</a></li>
                    <li class="nav-item"><a class="btn btn-dark" href="#">Log in</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="text-center py-5">
        <div class="container">
            <h1 class="display-4">FASHION IN FRAME</h1>
            <p class="lead">Where Every Outfit Becomes a Moment</p>
            <div class="input-group mb-3">
                <input type="text" class="form-control" placeholder="Explore">
                <button class="btn btn-primary" type="button">Search</button>
            </div>
        </div>
    </section>

    <!-- Designer Grid -->
    <section class="py-5">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 1.jpg" class="card-img-top" alt="hoodies">
                        <div class="card-body">
                            <p>hoodies</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 2.jpg" class="card-img-top" alt="combo">
                        <div class="card-body">
                            <p>combo</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 3.jpg" class="card-img-top" alt="shoes">
                        <div class="card-body">
                          <p>shoes</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 4.jpg" class="card-img-top" alt="accessories">
                        <div class="card-body">
                            <p>accessories</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 5.jpg" class="card-img-top" alt="crocs">
                        <div class="card-body">
                            <p>crocs</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 6.jpg" class="card-img-top" alt="watch">
                        <div class="card-body">
                            <p>watch</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 7.jpg" class="card-img-top" alt="tshirt">
                        <div class="card-body">
                            <p>tshirt</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 8.jpg" class="card-img-top" alt="sandals">
                        <div class="card-body">
                            <p>chappal</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img 9.jpg" class="card-img-top" alt="handbag">
                        <div class="card-body">
                            <p>handbag</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
<footer class="bg-light py-4">
        <div class="container text-center">
            <p class="mb-0 text-muted">&copy; 2025 Designed and Developed by Sathish Kumar .M</p>
        </div>
</footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot 2025-11-18 184440.png>)


![alt text](<Screenshot 2025-11-18 184504.png>)


![alt text](<Screenshot 2025-11-18 184519.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
