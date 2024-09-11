# bootstrap-5

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>My Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
  <style>

    body {
      padding-top: 60px; 
    }
    section {
      padding: 60px 0;
    }
    footer {
      position: relative;
      width: 100%;
      bottom: 0;
    }
  </style>
</head>
<body>



  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">My Bootstrap</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#portfolio">Portfolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section id="about" class="py-5" style="background-color: #f8f9fa;">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-8 text-center">
          <h2>Bootstrap 5</h2>
          <p>이것은 Bootstrap 입니다.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="portfolio" class="py-5">
    <div class="container">
      <h2 class="text-center mb-5">Bootstrap 5</h2>
      <div class="row">
      
        <div class="col-md-4 col-sm-6 mb-4">
          <div class="card">
            <img src="https://www.backmarket.co.kr/_next/image?url=https%3A%2F%2Fd1cgm1478039zi.cloudfront.net%2Fproduction%2Fresized_images%2Fsave_image%2F466x466_1019213316_6531220c4f280.jpg&w=640&q=75" class="card-img-top" alt="Project 1">
            <div class="card-body">
              <h5 class="card-title">Project 1</h5>
              <p class="card-text">This is a brief description of Project 1.</p>
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#project1Modal">Learn More</button>
            </div>
          </div>
        </div>

   
        <div class="col-md-4 col-sm-6 mb-4">
          <div class="card">
            <img src="https://www.backmarket.co.kr/_next/image?url=https%3A%2F%2Fd1cgm1478039zi.cloudfront.net%2Fproduction%2Fresized_images%2Fsave_image%2F466x466_1019213316_6531220c4f280.jpg&w=640&q=75" class="card-img-top" alt="Project 2">
            <div class="card-body">
              <h5 class="card-title">Project 2</h5>
              <p class="card-text">This is a brief description of Project 2.</p>
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#project2Modal">Learn More</button>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-6 mb-4">
          <div class="card">
            <img src="https://www.backmarket.co.kr/_next/image?url=https%3A%2F%2Fd1cgm1478039zi.cloudfront.net%2Fproduction%2Fresized_images%2Fsave_image%2F466x466_1019213316_6531220c4f280.jpg&w=640&q=75" class="card-img-top" alt="Project 3">
            <div class="card-body">
              <h5 class="card-title">Project 3</h5>
              <p class="card-text">This is a brief description of Project 3.</p>
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#project2Modal">Learn More</button>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-6 mb-4">
          <div class="card">
            <img src="https://www.backmarket.co.kr/_next/image?url=https%3A%2F%2Fd1cgm1478039zi.cloudfront.net%2Fproduction%2Fresized_images%2Fsave_image%2F466x466_1019213316_6531220c4f280.jpg&w=640&q=75" class="card-img-top" alt="Project 4">
            <div class="card-body">
              <h5 class="card-title">Project 4</h5>
              <p class="card-text">This is a brief description of Project 4.</p>
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#project2Modal">Learn More</button>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-6 mb-4">
          <div class="card">
            <img src="https://www.backmarket.co.kr/_next/image?url=https%3A%2F%2Fd1cgm1478039zi.cloudfront.net%2Fproduction%2Fresized_images%2Fsave_image%2F466x466_1019213316_6531220c4f280.jpg&w=640&q=75" class="card-img-top" alt="Project 5">
            <div class="card-body">
              <h5 class="card-title">Project 5</h5>
              <p class="card-text">This is a brief description of Project 5.</p>
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#project2Modal">Learn More</button>
            </div>
          </div>
        </div>

        <div class="col-md-4 col-sm-6 mb-4">
          <div class="card">
            <img src="https://www.backmarket.co.kr/_next/image?url=https%3A%2F%2Fd1cgm1478039zi.cloudfront.net%2Fproduction%2Fresized_images%2Fsave_image%2F466x466_1019213316_6531220c4f280.jpg&w=640&q=75" class="card-img-top" alt="Project 6">
            <div class="card-body">
              <h5 class="card-title">Project 6</h5>
              <p class="card-text">This is a brief description of Project 6.</p>
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#project2Modal">Learn More</button>
            </div>
          </div>
        </div>

        


      </div>
    </div>
  </section>


  <div class="modal fade" id="project1Modal" tabindex="-1" aria-labelledby="project1ModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="project1ModalLabel">Project 1 Details</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          아이폰 14 입니다 . 좋습니다.
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>

  <div class="modal fade" id="project2Modal" tabindex="-1" aria-labelledby="project2ModalLabel" aria-hidden="true">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="project2ModalLabel">Project 2 Details</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          아이폰 14 입니다 . 좋습니다..
        </div>
        <div class="modal-footer">
          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        </div>
      </div>
    </div>
  </div>


  <section id="contact" class="py-5" style="background-color: #f8f9fa;">
    <div class="container">
      <h2 class="text-center mb-4">Contact Me</h2>
      <div class="row justify-content-center">
        <div class="col-md-6">
          <form>
            <div class="mb-3">
              <label for="name" class="form-label">Name</label>
              <input type="text" class="form-control" id="name" required>
            </div>
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input type="email" class="form-control" id="email" required>
            </div>
            <div class="mb-3">
              <label for="message" class="form-label">Message</label>
              <textarea class="form-control" id="message" rows="3" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary w-100">Submit</button>
          </form>
        </div>
      </div>
    </div>
  </section>


  <footer class="bg-dark text-white py-3">
    <div class="container d-flex justify-content-between">
      <span>&copy; 2024 My Portfolio</span>
      <div>
        <a href="#" class="text-white me-2">Facebook</a>
        <a href="#" class="text-white me-2">Twitter</a>
        <a href="#" class="text-white">LinkedIn</a>
      </div>
    </div>
  </footer>


  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
