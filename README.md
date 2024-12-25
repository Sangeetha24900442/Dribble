# Project Responsive Web Design using Bootstrap
## Date:25.12.2024

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
  <title>Dribbble Clone - Responsive Web Design</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">MyDribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Explore</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="bg-light text-center py-5">
    <div class="container">
      <h1>Welcome to My Dribbble Clone</h1>
      <p class="lead">Showcase your creativity and explore amazing designs.</p>
      <a href="#" class="btn btn-primary">Get Started</a>
    </div>
  </section>

  <!-- Gallery Section -->
  <section class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Featured Designs</h2>
      <div class="row g-4">
        <div class="col-md-4">
          <img src="a.png" class="img-fluid rounded" alt="Design 1">
        </div>
        <div class="col-md-4">
          <img src="b.png" class="img-fluid rounded" alt="Design 2">
        </div>
        <div class="col-md-4">
          <img src="c.png" class="img-fluid rounded" alt="Design 3">
        </div>
        <div class="col-md-4">
            <img src="d.png" class="img-fluid rounded" alt="Design 4" onclick="openModal(this.src)">
          </div>
          <div class="col-md-4">
            <img src="e.png" class="img-fluid rounded" alt="Design 5" onclick="openModal(this.src)">
          </div>
          <div class="col-md-4">
            <img src="f.png" class="img-fluid rounded" alt="Design 6" onclick="openModal(this.src)">
          </div>
          <div class="col-md-4">
            <img src="g.png" class="img-fluid rounded" alt="Design 7" onclick="openModal(this.src)">
          </div>
          <div class="col-md-4">
            <img src="h.png" class="img-fluid rounded" alt="Design 8" onclick="openModal(this.src)">
          </div>
          <div class="col-md-4">
            <img src="i.png" class="img-fluid rounded" alt="Design 9" onclick="openModal(this.src)">
          </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <p>&copy; 2024 Sangeetha S (24900442). All Rights Reserved.</p>
    </div>
  </footer>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-12-25 203214.png>)
![alt text](<Screenshot 2024-12-25 203235.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
