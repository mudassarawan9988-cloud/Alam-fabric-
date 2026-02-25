<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALAM Fabrics | Premium Pakistani Textiles</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        :root { --emerald: #004d3d; --gold: #d4af37; --light: #fcfaf2; }
        body { font-family: 'Poppins', sans-serif; background-color: #fff; }
        .navbar-brand { font-family: 'Playfair Display', serif; color: var(--emerald) !important; font-weight: bold; }
        .hero { background: var(--emerald); color: white; padding: 80px 0; border-bottom: 5px solid var(--gold); }
        .text-gold { color: var(--gold) !important; }
        
        .product-card { border: none; transition: 0.3s shadow; }
        .product-card:hover { shadow: 0 10px 20px rgba(0,0,0,0.1); }
        
        /* WhatsApp Styling */
        .btn-whatsapp { background: #25d366; color: white; border-radius: 5px; font-weight: 600; text-decoration: none; padding: 10px; display: block; }
        .btn-whatsapp:hover { background: #128c7e; color: white; }
        
        .whatsapp-float { 
            position: fixed; bottom: 30px; right: 30px; 
            background: #25d366; color: white; 
            padding: 15px 25px; border-radius: 50px; 
            text-decoration: none; font-weight: bold;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            z-index: 1000;
            display: flex; align-items: center; gap: 10px;
        }
        .whatsapp-float:hover { color: #f1f1f1; transform: scale(1.05); transition: 0.3s; }
    </style>
</head>
<body>

<nav class="navbar navbar-light bg-white shadow-sm sticky-top">
    <div class="container text-center">
        <a class="navbar-brand mx-auto fs-2" href="#">ALAM <span class="text-gold">FABRICS</span></a>
    </div>
</nav>

<section class="hero text-center">
    <div class="container">
        <h1 class="display-4 fw-bold">Premium Quality Fabrics</h1>
        <p class="lead">Traditional Pakistani Textiles delivered to your doorstep.</p>
        <p class="badge bg-light text-dark p-2">Cash on Delivery Available Nationwide</p>
    </div>
</section>

<div class="container my-5">
    <h2 class="text-center mb-5 border-bottom pb-3">Our Collection</h2>
    <div class="row g-4 justify-content-center">
        
        <div class="col-md-4 col-10">
            <div class="card product-card shadow-sm h-100">
                <img src="https://via.placeholder.com/400x500/004d3d/ffffff?text=Lawn+Collection" class="card-img-top" alt="Fabric">
                <div class="card-body text-center">
                    <h5 class="fw-bold">Luxury Summer Lawn</h5>
                    <p class="text-gold fw-bold">Starting from Rs. 2,500</p>
                    <a href="https://wa.me/923054393658?text=Hello%20ALAM%20Fabrics!%20I%20want%20to%20order%20the%20Summer%20Lawn%20Collection." class="btn-whatsapp">
                        Order on WhatsApp
                    </a>
                </div>
            </div>
        </div>

        <div class="col-md-4 col-10">
            <div class="card product-card shadow-sm h-100">
                <img src="https://via.placeholder.com/400x500/d4af37/ffffff?text=Silk+Collection" class="card-img-top" alt="Fabric">
                <div class="card-body text-center">
                    <h5 class="fw-bold">Premium Silk Selection</h5>
                    <p class="text-gold fw-bold">Starting from Rs. 4,500</p>
                    <a href="https://wa.me/923054393658?text=Hello%20ALAM%20Fabrics!%20I%20am%20interested%20in%20your%20Silk%20Collection." class="btn-whatsapp">
                        Order on WhatsApp
                    </a>
                </div>
            </div>
        </div>

    </div>
</div>

<a href="https://wa.me/923054393658?text=Hello%20ALAM%20Fabrics!%20I%20have%20a%20question%20about%20your%20fabric." class="whatsapp-float" target="_blank">
    <span>Chat with us</span>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" width="25" alt="WA">
</a>

<footer class="text-center py-4 bg-light mt-5">
    <p class="text-muted mb-0">© 2026 ALAM Fabrics. Proudly Made in Pakistan.</p>
</footer>

</body>
</html>
