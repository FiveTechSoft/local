<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Local comercial en venta en Avenida del Trapiche, Marbella. 128 m², ubicación privilegiada en la avenida principal de Miraflores. Ideal para tienda, oficina o restaurante.">
    <meta name="keywords" content="local comercial, venta, Marbella, inmobiliaria, negocio">
    <meta name="author" content="Venta de Local">
    
    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://fivetech.es/">
    <meta property="og:title" content="Local Comercial en Venta - Madrid Gran Vía">
    <meta property="og:description" content="Excelente local comercial de 120 m² en zona comercial de Madrid. Precio: €180,000">
    <meta property="og:image" content="https://picsum.photos/1200/630?random=1">
    
    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image">
    <meta property="twitter:url" content="https://fivetech.es/">
    <meta property="twitter:title" content="Local Comercial en Venta - Madrid Gran Vía">
    <meta property="twitter:description" content="Excelente local comercial de 120 m² en zona comercial de Madrid. Precio: €180,000">
    <meta property="twitter:image" content="https://picsum.photos/1200/630?random=1">

    <title>Local Comercial en Venta - Madrid Gran Vía</title>

    <!-- Bootstrap 5 (CDN) -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

    <!-- Custom Styles -->
    <style>
        :root {
            --primary-color: #2c3e50;
            --accent-color: #3498db;
            --success-color: #27ae60;
            --light-bg: #f8f9fa;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
        }
        
        .navbar-brand {
            font-weight: bold;
            font-size: 1.5rem;
        }
        
        #hero {
            background: linear-gradient(135deg, var(--primary-color) 0%, var(--accent-color) 100%);
            min-height: 100vh;
            position: relative;
        }
        
        #hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('https://picsum.photos/1920/1080?random=10') center/cover;
            opacity: 0.1;
            z-index: 1;
        }
        
        #hero .container {
            position: relative;
            z-index: 2;
        }
        
        .property-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: none;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        
        .property-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }
        
        .gallery-item {
            cursor: pointer;
            transition: transform 0.3s ease;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .gallery-item:hover {
            transform: scale(1.05);
        }
        
        .price-badge {
            background: var(--success-color);
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 25px;
            font-weight: bold;
            font-size: 1.1rem;
        }
        
        .feature-icon {
            width: 60px;
            height: 60px;
            background: var(--accent-color);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5rem;
            margin: 0 auto 1rem;
        }
        
        .contact-form {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 2rem;
        }
        
        .btn-custom {
            background: var(--accent-color);
            border: none;
            padding: 12px 30px;
            border-radius: 25px;
            font-weight: 600;
            transition: all 0.3s ease;
        }
        
        .btn-custom:hover {
            background: #2980b9;
            transform: translateY(-2px);
        }
        
        .section-title {
            position: relative;
            margin-bottom: 3rem;
        }
        
        .section-title::after {
            content: '';
            position: absolute;
            bottom: -10px;
            left: 50%;
            transform: translateX(-50%);
            width: 50px;
            height: 3px;
            background: var(--accent-color);
        }
        
        .navbar {
            transition: all 0.3s ease;
        }
        
        .navbar.scrolled {
            background: rgba(44, 62, 80, 0.95) !important;
            backdrop-filter: blur(10px);
        }
        
        @media (max-width: 768px) {
            #hero h1 {
                font-size: 2.5rem;
            }
            
            .feature-icon {
                width: 50px;
                height: 50px;
                font-size: 1.2rem;
            }
        }
    </style>

    <!-- Favicon -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🏢</text></svg>">
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top py-3">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-building me-2"></i>Venta de Locales
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Alternar navegación">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link active" href="#sobre">Detalles</a></li>
                    <li class="nav-item"><a class="nav-link" href="#caracteristicas">Características</a></li>
                    <li class="nav-item"><a class="nav-link" href="#galeria">Galería</a></li>
                    <li class="nav-item"><a class="nav-link" href="#ubicacion">Ubicación</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header id="hero" class="text-white text-center d-flex align-items-center">
        <div class="container py-5">
            <h1 class="display-4 fw-bold mb-4">Local Comercial Excepcional</h1>
            <p class="lead mb-4">Ubicado en <strong>Madrid - Gran Vía</strong></p>
            <div class="price-badge mb-4">€180,000</div>
            <p class="fs-5 mb-4">120 m² • Zona comercial premium • Listo para entrar</p>
            <a href="#contacto" class="btn btn-light btn-lg btn-custom me-3">Solicitar Información</a>
            <a href="#galeria" class="btn btn-outline-light btn-lg">Ver Galería</a>
        </div>
    </header>

    <!-- Sección Sobre el Local -->
    <section id="sobre" class="py-5">
        <div class="container">
            <h2 class="text-center section-title">Detalles del Local</h2>
            <div class="row g-4 align-items-center">
                <div class="col-md-6">
                    <div class="property-card card h-100 p-4">
                        <h4 class="text-primary mb-3">Información Principal</h4>
                        <div class="row g-3">
                            <div class="col-6">
                                <p><i class="fas fa-expand-arrows-alt text-primary me-2"></i><strong>Superficie:</strong> 120 m²</p>
                                <p><i class="fas fa-store text-primary me-2"></i><strong>Tipo:</strong> Local comercial</p>
                            </div>
                            <div class="col-6">
                                <p><i class="fas fa-certificate text-primary me-2"></i><strong>Estado:</strong> Excelente</p>
                                <p><i class="fas fa-euro-sign text-primary me-2"></i><strong>Precio:</strong> €180,000</p>
                            </div>
                        </div>
                        <hr>
                        <p><strong>Descripción:</strong> Magnífico local comercial en la zona más comercial de Madrid. Perfecto para tienda de moda, restaurante, oficina o cualquier actividad comercial. Cuenta con gran escaparate, excelente visibilidad y alto tránsito peatonal.</p>
                        <div class="mt-3">
                            <span class="badge bg-success me-2">Licencia de actividad</span>
                            <span class="badge bg-info me-2">Aire acondicionado</span>
                            <span class="badge bg-warning">Gran escaparate</span>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <img src="https://picsum.photos/600/400?random=1" alt="Vista principal del local comercial" class="img-fluid rounded shadow-lg">
                </div>
            </div>
        </div>
    </section>

    <!-- Características -->
    <section id="caracteristicas" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center section-title">Características Destacadas</h2>
            <div class="row g-4">
                <div class="col-md-3 col-sm-6 text-center">
                    <div class="feature-icon">
                        <i class="fas fa-map-marker-alt"></i>
                    </div>
                    <h5>Ubicación Premium</h5>
                    <p>En plena Gran Vía de Madrid, zona de máximo tránsito comercial</p>
                </div>
                <div class="col-md-3 col-sm-6 text-center">
                    <div class="feature-icon">
                        <i class="fas fa-subway"></i>
                    </div>
                    <h5>Transporte Público</h5>
                    <p>Metro Gran Vía a 50m. Múltiples líneas de autobús disponibles</p>
                </div>
                <div class="col-md-3 col-sm-6 text-center">
                    <div class="feature-icon">
                        <i class="fas fa-lightbulb"></i>
                    </div>
                    <h5>Iluminación Natural</h5>
                    <p>Gran escaparate y ventanas que aportan excelente luminosidad</p>
                </div>
                <div class="col-md-3 col-sm-6 text-center">
                    <div class="feature-icon">
                        <i class="fas fa-tools"></i>
                    </div>
                    <h5>Listo para Usar</h5>
                    <p>Instalaciones completas y en perfecto estado de conservación</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Galería -->
    <section id="galeria" class="py-5">
        <div class="container">
            <h2 class="text-center section-title">Galería de Imágenes</h2>
            <div class="row g-3">
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=2" class="img-fluid rounded gallery-item shadow" alt="Exterior del local" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=2">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=3" class="img-fluid rounded gallery-item shadow" alt="Interior amplio" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=3">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=4" class="img-fluid rounded gallery-item shadow" alt="Zona de exposición" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=4">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=5" class="img-fluid rounded gallery-item shadow" alt="Vista desde la calle" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=5">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=6" class="img-fluid rounded gallery-item shadow" alt="Detalles interiores" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=6">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=7" class="img-fluid rounded gallery-item shadow" alt="Escaparate principal" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=7">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=8" class="img-fluid rounded gallery-item shadow" alt="Zona de almacén" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=8">
                </div>
                <div class="col-6 col-md-3">
                    <img src="https://picsum.photos/400/300?random=9" class="img-fluid rounded gallery-item shadow" alt="Acceso principal" data-bs-toggle="modal" data-bs-target="#imageModal" data-bs-image="https://picsum.photos/800/600?random=9">
                </div>
            </div>
        </div>
    </section>

    <!-- Modal para Galería -->
    <div class="modal fade" id="imageModal" tabindex="-1" aria-labelledby="imageModalLabel" aria-hidden="true">
        <div class="modal-dialog modal-lg modal-dialog-centered">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="imageModalLabel">Galería del Local</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Cerrar"></button>
                </div>
                <div class="modal-body text-center">
                    <img id="modalImage" src="" alt="Imagen del local" class="img-fluid rounded">
                </div>
            </div>
        </div>
    </div>

    <!-- Ubicación -->
    <section id="ubicacion" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center section-title">Ubicación Privilegiada</h2>
            <div class="row g-4">
                <div class="col-md-8">
                    <div class="ratio ratio-16x9 rounded overflow-hidden shadow">
                        <iframe
                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3037.4846416493983!2d-3.701571!3d40.4202234!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0xd4228c4c3b5b7a5%3A0x8b8c7a8b6b6b6b6b!2sGran%20V%C3%ADa%2C%20Madrid%2C%20Spain!5e0!3m2!1sen!2sus!4v1647353086242!5m2!1sen!2sus"
                            style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100 p-4">
                        <h4 class="text-primary mb-3">
                            <i class="fas fa-map-marker-alt me-2"></i>Dirección
                        </h4>
                        <p class="mb-3"><strong>Gran Vía, 45<br>28013 Madrid, España</strong></p>
                        
                        <h5 class="text-primary mb-3">Transporte Público</h5>
                        <ul class="list-unstyled">
                            <li class="mb-2"><i class="fas fa-subway text-info me-2"></i>Metro Gran Vía (L1, L5) - 50m</li>
                            <li class="mb-2"><i class="fas fa-subway text-info me-2"></i>Metro Callao (L3, L5) - 200m</li>
                            <li class="mb-2"><i class="fas fa-bus text-success me-2"></i>Múltiples líneas de autobús</li>
                        </ul>
                        
                        <h5 class="text-primary mb-3">Servicios Cercanos</h5>
                        <ul class="list-unstyled">
                            <li class="mb-1"><i class="fas fa-shopping-bag text-warning me-2"></i>Zona comercial</li>
                            <li class="mb-1"><i class="fas fa-utensils text-danger me-2"></i>Restaurantes</li>
                            <li class="mb-1"><i class="fas fa-hotel text-info me-2"></i>Hoteles</li>
                            <li class="mb-1"><i class="fas fa-theater-masks text-purple me-2"></i>Teatros</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto" class="py-5" style="background: linear-gradient(135deg, var(--primary-color) 0%, var(--accent-color) 100%);">
        <div class="container">
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <h2 class="text-center section-title text-white">Contacta con Nosotros</h2>
                    <div class="contact-form">
                        <form id="contactForm" class="needs-validation" novalidate>
                            <div class="row g-3">
                                <div class="col-md-6">
                                    <label for="nombre" class="form-label text-white">
                                        <i class="fas fa-user me-2"></i>Nombre Completo
                                    </label>
                                    <input type="text" class="form-control form-control-lg" id="nombre" required>
                                    <div class="invalid-feedback">Por favor, ingresa tu nombre.</div>
                                </div>
                                <div class="col-md-6">
                                    <label for="telefono" class="form-label text-white">
                                        <i class="fas fa-phone me-2"></i>Teléfono
                                    </label>
                                    <input type="tel" class="form-control form-control-lg" id="telefono" required>
                                    <div class="invalid-feedback">Por favor, ingresa tu teléfono.</div>
                                </div>
                                <div class="col-12">
                                    <label for="email" class="form-label text-white">
                                        <i class="fas fa-envelope me-2"></i>Email
                                    </label>
                                    <input type="email" class="form-control form-control-lg" id="email" required>
                                    <div class="invalid-feedback">Por favor, ingresa un email válido.</div>
                                </div>
                                <div class="col-12">
                                    <label for="mensaje" class="form-label text-white">
                                        <i class="fas fa-comment me-2"></i>Mensaje
                                    </label>
                                    <textarea class="form-control form-control-lg" id="mensaje" rows="4" placeholder="Cuéntanos sobre tu interés en este local..." required></textarea>
                                    <div class="invalid-feedback">Por favor, escribe tu consulta.</div>
                                </div>
                            </div>
                            <div class="text-center mt-4">
                                <button type="submit" class="btn btn-light btn-lg btn-custom px-5">
                                    <i class="fas fa-paper-plane me-2"></i>Enviar Consulta
                                </button>
                            </div>
                        </form>
                    </div>
                    
                    <div class="row g-4 mt-4 text-white text-center">
                        <div class="col-md-4">
                            <div class="feature-icon bg-light text-primary">
                                <i class="fas fa-phone"></i>
                            </div>
                            <h5>Teléfono</h5>
                            <p>+34 91 123 4567</p>
                        </div>
                        <div class="col-md-4">
                            <div class="feature-icon bg-light text-primary">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <h5>Email</h5>
                            <p>info@ventalocales.es</p>
                        </div>
                        <div class="col-md-4">
                            <div class="feature-icon bg-light text-primary">
                                <i class="fas fa-clock"></i>
                            </div>
                            <h5>Horario</h5>
                            <p>Lun-Vie: 9:00-19:00<br>Sáb: 10:00-14:00</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-md-6">
                    <p class="mb-0">&copy; 2025 Venta de Locales. Todos los derechos reservados.</p>
                </div>
                <div class="col-md-6 text-md-end">
                    <div class="social-links">
                        <a href="#" class="text-white me-3"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-white me-3"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-white me-3"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-white"><i class="fab fa-linkedin-in"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    
    <!-- Custom JavaScript -->
    <script>
        // Navbar scroll effect
        window.addEventListener('scroll', function() {
            const navbar = document.querySelector('.navbar');
            if (window.scrollY > 100) {
                navbar.classList.add('scrolled');
            } else {
                navbar.classList.remove('scrolled');
            }
        });

        // Gallery modal functionality
        const imageModal = document.getElementById('imageModal');
        imageModal.addEventListener('show.bs.modal', function (event) {
            const button = event.relatedTarget;
            const imageSrc = button.getAttribute('data-bs-image');
            const modalImage = document.getElementById('modalImage');
            modalImage.src = imageSrc;
        });

        // Form validation and submission
        const contactForm = document.getElementById('contactForm');
        contactForm.addEventListener('submit', function(event) {
            event.preventDefault();
            event.stopPropagation();

            if (contactForm.checkValidity()) {
                // Show success message
                const button = contactForm.querySelector('button[type="submit"]');
                const originalText = button.innerHTML;
                button.innerHTML = '<i class="fas fa-check me-2"></i>¡Mensaje Enviado!';
                button.classList.replace('btn-custom', 'btn-success');
                
                setTimeout(() => {
                    button.innerHTML = originalText;
                    button.classList.replace('btn-success', 'btn-custom');
                    contactForm.reset();
                    contactForm.classList.remove('was-validated');
                }, 3000);
            }

            contactForm.classList.add('was-validated');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
    </script>
</body>
</html>
