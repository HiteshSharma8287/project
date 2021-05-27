<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shape Ai</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
        integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

</head>

<body>

    <!-- Nav Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
        <div class="container-fluid">
            <a class="navbar-brand text-white" href="#">Hitesh Sharma</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#hero">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#skills">My Skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#works">My Works</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact me</a>
                    </li>
                </ul>

            </div>
        </div>
    </nav>

    <main class="container mt-3">
        <section id="hero"
            class="d-flex justify-content-sm-center justify-content-md-evenly align-items-center flex-column-reverse gap-3 flex-md-row">
            <!-- Hero -->
            <div
                class="d-flex justify-content-sm-center align-items-center flex-column flex-md-column justify-content-md-start align-items-md-start">
                <h5>Hi!👋</h5>
                <h1>I'm Hitesh Sharma</h1>
                <p>A full stack web developer!</p>
                <button class="btn btn-dark btn-sm">My cool Resume 🧒 </button>
            </div>
            <div class="d-md-none w-50 w-50">
                <img src="ht.png" alt="" class="w-100 h-100 rounded-circle shadow">
            </div>
            <div class=" d-none d-md-block w-25 h-25">
                <img src="ht.png" alt="" class="w-100 h-100 rounded-circle shadow">
            </div>
        </section>

        <section id="skills" class=" mt-5  p-2 rounded d-flex flex-column justify-content-sm-center">
            <!-- My skills -->
            <h1 class="text-dark text-center">My Skill Set</h1>
            <div class="mt-3 d-md-none d-flex  justify-content-sm-evenly">
                <i class="fab fa-html5 fa-4x " style="color: #f4470b;"></i>
                <i class="fab fa-css3 fa-4x text-primary"></i>
                <i class="fab fa-bootstrap fa-4x" style="color:rgb(190,75,219);"></i>

            </div>
            <div class="mt-4 d-none d-md-flex  justify-content-sm-evenly">
                <i class="fab fa-html5 fa-7x " style="color: #f4470b;"></i>
                <i class="fab fa-css3 fa-7x text-primary"></i>
                <i class="fab fa-bootstrap fa-7x" style="color:rgb(190,75,219);"></i>

            </div>
        </section>

        <section id="works" class=" mt-4  p-5">
            <!-- My works -->
            <h1 class="text-dark text-center">My Works</h1>
            <div class="d-flex flex-column flex-md-row justify-content-md-evenly gap-3">
                <div class="card mb-2">
                    <img src="122.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Portfolio Website</h5>
                        <p class="card-text">Bulit an amazing responsive Website With bootstrap</p>
                        <a href="#" class="btn btn-dark">View Source <i class="fab fa-github"></i></a>
                    </div>
                </div>
                <div class="card mb-2">
                    <img src="122.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Portfolio Website</h5>
                        <p class="card-text">Bulit an amazing responsive Website With bootstrap</p>
                        <a href="#" class="btn btn-dark">View Source <i class="fab fa-github"></i></a>
                    </div>
                </div>
                <div class="card mb-2">
                    <img src="122.jpg" class="card-img-top" alt="...">
                    <div class="card-body">
                        <h5 class="card-title">Portfolio Website</h5>
                        <p class="card-text">Bulit an amazing responsive Website With bootstrap</p>
                        <a href="#" class="btn btn-dark">View Source <i class="fab fa-github"></i></a>
                    </div>
                </div>
            </div>


        </section>

        <section id="contact" class="mt-2 py-2">
            <!-- Contact me -->
                <h1 class="text-dark text-center">Contact Form</h1>
                <div class="row">
                    <div class="col-sm col-md-8">
                <form >
                <div class="mb-3">
                    <label for="exampleFormControlInput1" class="form-label">Email address</label>
                    <input type="email" required class="form-control" id="exampleFormControlInput1"
                        placeholder="name@example.com">
                </div>
                <div class="mb-3">
                    <label for="exampleFormControlTextarea1" class="form-label">Your Message</label>
                    <textarea class="form-control" id="exampleFormControlTextarea1" required
                        placeholder="Enter tour amazing messages!" rows="3"></textarea>
                </div>
                <button type="submit" class="btn btn-dark">Submit</button>
            </form>
        </div>
        <div class=" col-sm col-md-4">
            <div class="mt-4">
                <h4><i class="fas fa-at text-dark">hiteshsarmap83@gmail.com</i></h4>
                <button type="button" class="btn btn-link btn-outline-dark">
                    <a href="https://github.com/join"><i class="fab fa-github"></i></a>
                </button>
            </div>
        </div>
        </div>
        </section>

    </main>













    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
        crossorigin="anonymous"></script>

</body>

</html>
