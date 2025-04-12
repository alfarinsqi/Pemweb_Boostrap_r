# Pemweb_Boostrap_r 
# index.html  

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nayuga Website</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark" style="background-color: #ff66b2;">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Nayuga Website</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="text-center py-5" style="background-color: #ffe6f0;">
    <div class="container">
      <h1 class="display-5 fw-bold" style="color: #cc0066;">Welcome to Nayuga Website</h1>
      <p class="lead text-muted">let's get acquainted and find out more!</p>
      <a href="#layanan" class="btn" style="background-color: #ff66b2; color: white;">explore services</a>
    </div>
  </header>

  <!-- Services Section -->
  <section id="layanan" class="py-5">
    <div class="container text-center">
      <h2 class="mb-4" style="color: #cc0066;">About me</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card h-100 shadow-sm border-0">
            <div class="card-body">
              <h5 class="card-title" style="color: #ff3399;">TIKTOK</h5>
              <p class="card-text">@payyinn</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card h-100 shadow-sm border-0">
            <div class="card-body">
              <h5 class="card-title" style="color: #ff3399;">INSTAGRAM</h5>
              <p class="card-text">@alfarinsqinay</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card h-100 shadow-sm border-0">
            <div class="card-body">
              <h5 class="card-title" style="color: #ff3399;">Whatsapp</h5>
              <p class="card-text">082184566238</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-white text-center py-3" style="background-color: #ff66b2;">
    <div class="container">
      <p class="mb-0">&copy; 2025 Nayuga Website. All rights reserved.</p>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

# style.css
body {
    background-color: #fff0f5;
  }
  .card {
    transition: transform 0.3s ease;
  }
  .card:hover {
    transform: scale(1.03);
  }
  
