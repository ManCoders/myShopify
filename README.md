<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>myShopify Dashboard</title>
    <meta name="p:domain_verify" content="e7ba74d138599bdf87448544bb002386" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <div class="container  mt-4">
        <div class="container-fluid">
            <nav class="navbar navbar-expand-lg bg-body-tertiary">
                <div class="container-fluid d-flex justify-content-between align-items-center ">
                    <a class="navbar-brand" href="#">myShopify</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                        aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse " id="navbarSupportedContent">
                        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Contact</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">About</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Services</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Portfolio</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
    </div>

    <script>
        function myFunction() {
            var x = document.getElementById("myTopnav");
            if (x.className === "topnav") {
                x.className += " responsive";
            } else {
                x.className = "topnav";
            }
        }
    </script>


    <div class="container">
        <div class=" d-flex justify-content-center align-items-center">
            
            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title" id="card-title">Card title</h5>
                                    <a href="#" id="link" class="link">See all </a>
                                </div>
                                <img id="card-img" src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1" id="card-text">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" id="btn" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <script>
                // Add event listener to the button
                document.getElementById("btn").addEventListener("click", function() {
                  // Get the product details
                  var title = document.getElementById("card-title").innerText;
                  var description = document.getElementById("card-text").innerText;
                  var imageURL = document.getElementById("card-img").src;
              
                  // Store product details in localStorage
                  localStorage.setItem("productTitle", title);
                  localStorage.setItem("productDescription", description);
                  localStorage.setItem("productImageURL", imageURL);
              
                  // Navigate to the shop page
                  window.location.href = "https://www.amazon.com/Jabra-Elite-Active-Comfortable-Cancellation/dp/B0CB9563MB";
                });
              </script>




            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container mt-2 mb-2">
                <div class="cul">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container">
        <div class=" d-flex justify-content-center align-items-center">
            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container mt-2 mb-2">
                <div class="cul">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <div class=" d-flex justify-content-center align-items-center">
            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="container mt-2 mb-2">
                <div class="cul">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title">Card title</h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <img src="https://source.unsplash.com/random/300x300" class="card-img-top img-fluid"
                                    alt="...">
                                <p class="card-text mt-1">Some quick example text to build on the card title and make up
                                    the bulk of the card's content.</p>
                                <a href="#" class="btn btn-primary">Go somewhere</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <div class="container">
        <div class=" d-flex justify-content-center align-items-center">
            <div class="container mt-2 mb-2">
                <div class="row">
                    <div class="col">
                        <div class="card">
                            <div class="card-body">
                                <div class="d-flex justify-content-between align-items-center">
                                    <h5 class="card-title"><h class="card-title">Thank You for Visiting!</h></h5>
                                    <a href="#" class="link">See all </a>
                                </div>
                                <div class="card-text">
                                    <p>&copy; 2024 Your Website. All rights reserved.</p>
                                    <p>Email me at <a href="mailto:QsLbF@example.com">Daligdig.Manuel19@example.com</a></p>
                                    <p>Designed with <i class="bi"></i> by MattIwago</p>
                                </div>
                            </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Bootstrap JavaScript (optional) via CDN -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
