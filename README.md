# Ex.10 Responsive Web Design using Bootstrap

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
``` C
[10:22 AM, 5/15/2024] Rajkiran Cse: <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - RISHI Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RISHI Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/web.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to RISHI Company</h1>
        <p>Welcome to  Dr. RISHI Laboratories, your trusted source for high-quality pharmaceutical products. We are dedicated to improving the health and well-being of our customers by providing safe and effective medications.</p>
        <p>At Dr. RISHI Laboratories, we offer a wide range of prescription and over-the-counter medications to meet your healthcare needs. Whether you're managing a chronic condition or simply looking for relief from minor ailments, we have the products you need.</p>
        <p>In addition to medications, we also carry a variety of healthcare products and accessories, including vitamins, supplements, first aid supplies, and more. Our knowledgeable staff is here to assist you with any questions you may have and to ensure you find the right products for your needs.</p>
        <p>Thank you for choosing PharmaCompany for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="C:\Users\Rajkiran\Downloads\M.jpg" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>
  <body background="C:\Users\Rajkiran\Downloads\bacKground.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 RISHI Company. All rights reserved. BY RISHI KEERTHI.K(212222043007)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
[10:22 AM, 5/15/2024] Rajkiran Cse: <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About RISHI Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RISHI Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/web.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="file:///C:/Users/Rajkiran/about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">vision</a>
            <a class="dropdown-item" href="#mission">mission</a>
            <a class="dropdown-item" href="#values">values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About RISHI Company</h1>
        <div id="vision">
            <h2 style="font-size:1cm">Vision</h2>
            <p style="font-size: larger;">Our vision is to be a leading provider of innovative healthcare solutions that improve the quality of life for people around the world.</p>
          </div>
          <div id="mission">
            <h2 style="font-size: 1cm;">Mission</h2>
            <p style="font-size: larger;">Our mission is to develop and deliver safe, effective, and affordable medications that address the healthcare needs of our customers.</p>
          </div>
        <div id="values">
          <h2>values</h2>
          <ul>
            <li>Quality: We are committed to maintaining the highest standards of quality in everything we do.</li>
            <li>Integrity: We conduct our business with honesty, transparency, and ethical behavior.</li>
            <li>Innovation: We strive to continuously innovate and improve our products and services to better serve our customers.</li>
            <li>Customer Focus: We are dedicated to understanding and meeting the needs of our customers.</li>
            <li>Teamwork: We work together as a team to achieve our goals and deliver exceptional results.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="C:\Users\Rajkiran\Downloads\background.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 RISHI Company. All rights reserved.  BY RISHI KEERTHI.K(212222043007)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
[10:22 AM, 5/15/2024] Rajkiran Cse: <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - RISHI Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RISHI Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="C:\Users\Rajkiran\Downloads\product1.jpg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Rituximab injection is used alone or together with other medicines to treat a type of cancer called non-Hodgkin's lymphoma (NHL). It is also used in combination with other cancer medicines to treat mature B-cell non-Hodgkin's lymphoma (NHL) and mature B-cell acute leukemia (B-AL).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="C:\Users\Rajkiran\Downloads\product2.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Rivaroxaban is used to treat and prevent deep venous thrombosis (DVT), a condition in which harmful blood clots form in the blood vessels of the legs. These blood clots can travel to the lungs and can become lodged in the blood vessels of the lungs, causing a condition called pulmonary embolism (PE).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="C:\Users\Rajkiran\Downloads\product3.jpg" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Aflibercept is a medication used to treat and manage neovascular age-related macular degeneration, diabetic macular edema, myopic choroidal neovascularization, macular edema associated with retinal vein occlusion, and diabetic retinopathy.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 RISHI Company. All rights reserved.  BY RISHI KEERTHI.K(212222043007)</p>
  </footer>
  <body background="C:\Users\Rajkiran\Downloads\background.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
[10:22 AM, 5/15/2024] Rajkiran Cse: <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - RISHI Company</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">RISHI Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="file:///C:/Users/Rajkiran/contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>RISHI Company</h2>
        <address>
          <strong>Address:</strong><br>
          123 xyz street, Chennai<br>
          India, 632007<br><br>
          <strong>Email:</strong><br>
          info@RISHIcompany.com<br><br>
          <strong>Phone:</strong><br>
          +1432789560
        </address>
      </div>
    </div>
  </div>
  <body background="C:\Users\Rajkiran\Downloads\background.jpg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 RISHI Company. All rights reserved.  BY RISHI KEERTHI.K(212222043007)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![p1](https://github.com/RISHIKEERTHI14605/Pharma/assets/147148903/10006879-eaa4-43c7-a905-adfc0ecf3681)
![p2](https://github.com/RISHIKEERTHI14605/Pharma/assets/147148903/ebd22073-84aa-4c01-9c25-c9767bb022ea)
![p3](https://github.com/RISHIKEERTHI14605/Pharma/assets/147148903/f60c428f-43fb-450f-930f-8fad80a9360f)
![p4](https://github.com/RISHIKEERTHI14605/Pharma/assets/147148903/8e68d355-4264-4fa8-b2f2-81572761352c)


## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
