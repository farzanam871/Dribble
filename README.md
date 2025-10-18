# Project Responsive Web Design using Bootstrap
## Date:16.10.2025

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
  <title>Dribbble Gallery</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body class="bg-light vh-100 overflow-hidden d-flex flex-column">
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark py-2">
    <div class="container-fluid">
      <a class="navbar-brand fw-bold" href="#">Dribbble</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item"><a class="nav-link active" href="#">Shots</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Community</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
        </ul>
        <form class="d-flex">
          <input class="form-control form-control-sm me-2" type="search" placeholder="Search">
          <button class="btn btn-outline-light btn-sm" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <div class="bg-dark border-bottom text-center py-1">
    <h6 class="text-white mb-0">What are you working on?</h6>
    <small class="text-light">Dribbble is show and tell for designers.</small><br>
    <button class="btn btn-danger btn-sm mt-1">Sign up</button>
  </div>
  <div class="container border-top py-2 text-center">
    <div class="d-inline-flex justify-content-center gap-2 flex-wrap">
      <div class="dropdown">
        <button class="btn btn-sm dropdown-toggle" type="button" data-bs-toggle="dropdown">
          Popular
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Popular</a></li>
          <li><a class="dropdown-item" href="#">New & Noteworthy</a></li>
          <li><a class="dropdown-item" href="#">Following</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button class="btn btn-sm dropdown-toggle" type="button" data-bs-toggle="dropdown">
          Shots
        </button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">All</a></li>
          <li><a class="dropdown-item" href="#">Mobile</a></li>
          <li><a class="dropdown-item" href="#">Web</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <button class="btn btn-sm dropdown-toggle" type="button" data-bs-toggle="dropdown">Now</button>
        <ul class="dropdown-menu">
          <li><a class="dropdown-item" href="#">Now</a></li>
          <li><a class="dropdown-item" href="#">This Week</a></li>
          <li><a class="dropdown-item" href="#">This Month</a></li>
        </ul>
      </div>
    </div>
  </div>
  <div class="container-fluid flex-grow-1 d-flex align-items-center justify-content-center">
    <div class="row g-2 w-100 justify-content-center px-2">
      <div class="col-2">
        <div class="card border-0 shadow-sm text-center">
          <img src="famous.png" class="card-img-top">
          <div class="card-body p-1">
            <small class="fw-semibold d-block">Ferrari 296 GTB</small>
            <small class="text-muted">7,382 views • 272 likes</small>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card border-0 shadow-sm text-center">
            <img src="balkanbrother.jpg" class="card-img-top">
            <div class="card-body p-1">
                <small class="fw-semibold d-block">Ferrari Purosangue</small>
                <small class="text-muted">3,054 views • 500 likes</small>
            </div>
        </div>
    </div>
      <div class="col-2">
        <div class="card border-0 shadow-sm text-center">
          <img src="Mattias.png" class="card-img-top">
          <div class="card-body p-1">
            <small class="fw-semibold d-block">Ferrari First Electric Car</small>
            <small class="text-muted">3,054 views • 500 likes</small>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card border-0 shadow-sm text-center">
          <img src="e.png" class="card-img-top">
          <div class="card-body p-1">
            <small class="fw-semibold d-block">Ferrari Monza SPT</small>
            <small class="text-muted">7,432 views • 260 likes</small>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card border-0 shadow-sm text-center">
          <img src="image.png" class="card-img-top">
          <div class="card-body p-1">
            <small class="fw-semibold d-block">Ferrai Roma</small>
            <small class="text-muted">8,322 views • 940 likes</small>
          </div>
        </div>
      </div>
      <div class="col-2">
        <div class="card border-0 shadow-sm text-center">
          <img src="image1.png" class="card-img-top">
          <div class="card-body p-1">
            <small class="fw-semibold d-block">Ferrari Daytona SP3</small>
            <small class="text-muted">7,342 views • 240 likes</small>
          </div>
        </div>
      </div>
     

    </div>
  </div>
  <footer class="bg-dark text-light text-center py-1">
    <small>&copy; 2025 Dribbble | Farzana M (25013772)</small>
  </footer>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2025-10-15 234523.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
