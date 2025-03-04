<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajesh Travel & Tourism</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        *{
            font-family:'Times New Roman', Times, serif;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
        }
        .navbar {
            background-color: #007bff;
        }
        .carousel-item img {
            width: 100%;
            height: 500px;
            object-fit: cover;
        }
        .section {
            padding: 60px 20px;
            text-align: center;
        }
        footer {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand text-white" href="#">Rajesh Travel & Tourism</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#about">About Us</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#packages">Packages</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://media.istockphoto.com/id/1031430214/photo/young-woman-kayaking-through-the-backwaters-of-monroe-island.webp?a=1&b=1&s=612x612&w=0&k=20&c=BaGIQLeJVZAFy3ktpPYfhFhvXNv3yGltWcOzljwZUUc=" class="d-block w-100" alt="Slide 1">
            </div>
            <div class="carousel-item">
                <img src="https://images.unsplash.com/photo-1740129753406-3e8feed29b4c?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTZ8fHRyYXZlbCUyMCUyNiUyMHRvdXJpc20lMjBpbmRpYXxlbnwwfHwwfHx8MA%3D%3D" class="d-block w-100" alt="Slide 2">
            </div>
            <div class="carousel-item">
                <img src="https://media.istockphoto.com/id/1059091470/photo/couple-on-the-shore-of-paradise-island.webp?a=1&b=1&s=612x612&w=0&k=20&c=YuyP_Mm-e5rTZN2heTODA4c6BTYxn03dRp-j2RzLHdE=" class="d-block w-100" alt="Slide 3">
            </div>
            <div class="carousel-item">
                <img src="https://images.unsplash.com/photo-1597074866923-dc0589150358?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MzZ8fHRyYXZlbCUyMCUyNiUyMHRvdXJpc20lMjBpbmRpYXxlbnwwfHwwfHx8MA%3D%3D" class="d-block w-100" alt="Slide 3">
            </div>


        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
    <div id="about" class="section container">
        <h2>About Us</h2>
        <p class="text-primary h4" style="text-align: justify;">Rajesh Travel & Tourism has been a trusted name in the travel industry for over 20 years. Based in Tughlakabad Extension, we specialize in providing customized travel packages to all states of India. Our mission is to make your journey seamless and memorable with our expert planning and extensive network. Whether you seek adventure, cultural experiences, or relaxing getaways, we have the perfect package for you. With a commitment to customer satisfaction, we ensure hassle-free travel, top-notch accommodations, and unforgettable experiences. Let us take care of your travel needs while you focus on making lifelong memories.</p>    </div>
        <div id="packages" class="section container-fluid bg-warning">
            <h1 style="font-weight: 800;">Our Packages</h1>
            <p>Discover amazing destinations with our customized travel packages.</p>
            <div class="row">
                <div class="col-md-4">
                    <h3>Golden Triangle Tour</h3>
                    <p class="text-danger h4" style="text-align: justify;">
                        <img class="w-100" src="https://images.unsplash.com/photo-1564507592333-c60657eea523?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8dGFqJTIwbWFoYWx8ZW58MHx8MHx8fDA%3D" alt="">Explore Delhi, Agra, and Jaipur with our exclusive Golden Triangle package. Visit historical monuments like the Taj Mahal, Red Fort, and Amber Fort.</p>
                </div>
                <div class="col-md-4">
                    <h3>Kerala Backwaters</h3>
                    <img class="w-100" src="https://images.unsplash.com/photo-1602216056096-3b40cc0c9944?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8a2VyYWxhfGVufDB8fDB8fHww" alt="">
                    <p class="text-danger h4" style="text-align: justify;">Enjoy the tranquil beauty of Kerala with a houseboat stay in Alleppey, lush tea gardens in Munnar, and scenic beaches in Kovalam.</p>
                </div>
                <div class="col-md-4">
                    <h3>Goa Beach Getaway</h3>
                    <img class="w-100" src="https://images.unsplash.com/photo-1614082242765-7c98ca0f3df3?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8N3x8Z29hJTIwYmVhY2h8ZW58MHx8MHx8fDA%3D" alt="">
                    <p class="text-danger h4" style="text-align: justify;">Relax on the pristine beaches of Goa, experience vibrant nightlife, and explore Portuguese heritage sites in this ultimate beach destination.</p>
                </div>
            </div>
        </div>
    <div id="contact" class="section container">
        <h2>Contact Us</h2>
        <p>Email: info@rajeshtravel.com | Phone: +91 9812514220</p>
    </div>
    <div class="gallery container-fluid bg-warning">
        <h1 class="text-center mb-4" style="font-weight: 800;">Image Gallery</h1>
        <div class="row">
            <div class="col-md-4 mb-3">
                <img src="https://plus.unsplash.com/premium_photo-1661963369594-9b25cd53be4d?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDF8fHRyYXZlbCUyMCUyNiUyMHRvdXJpc20lMjBpbmRpYXxlbnwwfHwwfHx8MA%3D%3D" alt="Gallery Image 1" class="img-fluid">
            </div>
            <div class="col-md-4 mb-3">
                <img src=https://plus.unsplash.com/premium_photo-1661964446598-630884d8d1c9?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDl8fHRyYXZlbCUyMCUyNiUyMHRvdXJpc20lMjBpbmRpYXxlbnwwfHwwfHx8MA%3D%3D" alt="Gallery Image 2" class="img-fluid">
            </div>
            <div class="col-md-4 mb-3">
                <img src="https://plus.unsplash.com/premium_photo-1734581717792-8c9009bdc811?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NTd8fHRyYXZlbCUyMCUyNiUyMHRvdXJpc20lMjBpbmRpYXxlbnwwfHwwfHx8MA%3D%3D" alt="Gallery Image 3" class="img-fluid">
            </div>
        </div>
    </div>    <footer>
        &copy; 2025 Rajesh Travel & Tourism. All rights reserved.
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
