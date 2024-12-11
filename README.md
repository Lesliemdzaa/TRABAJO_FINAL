<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boutique "El Tacón Travieso"</title>
    <link rel ="stylesheet" href="principal.css"/>
</head>
<body>
    <header class="he">
        <h1>Boutique "El Tacón Travieso"</h1>
    </header>

    <nav>
        <a href="inicio.html">Inicio</a>
        <a href="catalogo.html">Catálogo</a>
        <a href="ofertas.html">Ofertas</a>
        <a href="acerca.html">Acerca de Nosotros</a>
        <a href="contacto.html">Contacto</a>
    </nav>


        <section id="inicio" class="hero">
            <p class="texto">Descubre lo último en moda, calzado y accesorios.</p>
        </section>


        <section id="catalogo">
            <h2 class="catalogo">Catálogo</h2>
                <div class="catalog-item ">
                    <img class="imge" src="imagenes/ropa.png"/>
                    <h3>Prendas de Moda</h3>
                    <p>Vestidos, blusas, pantalones y más.</p>
                </div>
                <div class="catalog-item">
                    <img class="imge" src="imagenes/zapatos.png"/>
                    <h3>Zapatos</h3>
                    <p>Tacones, zapatillas y botas.</p>
                </div>
                <div class="catalog-item">
                    <img class="imge" src="imagenes/accesorios.png"/>
                    <h3>Accesorios</h3>
                    <p>Bolsos, joyería, cinturones y más.</p>
                </div>
                <div class="boton-container">
                    <button class="botonver" onclick="location.href='catalogo.html'">Ver Catálogo</button>
                </div>

        </section>

        <section class="ofer" id="ofertas">
            <img class="imgg" src="imagenes/ofertas (1).png"/>
            <div class="margin">
                <h2 class="catalogo">Ofertas por Temporada</h2>
                <p class="pp">¡Descubre las mejores promociones del momento!</p>
                <div class="boton-container">
                    <button class="botonver" onclick="location.href='ofertas.html'">Ver Ofertas</button>
                </div>
            </div>
        </section>  

    <footer class="foote">
        <p>&copy; 2024 Boutique "El Tacón Travieso". Todos los derechos reservados.</p>
        <p class="contact-info">📞 Teléfono: 123-456-7890 | 📧 Correo: contacto@eltacontravieso.com</p>
        <div class="social-icons">
            <a href="https://www.facebook.com" target="_blank" aria-label="Facebook">
                <img src="IMG/facebook.jpg" alt="Facebook">
            </a>
            <a href="https://www.instagram.com" target="_blank" aria-label="Instagram">
                <img src= "IMG/INSTA.jpg" alt="Instagram">
            </a>
        </div>
    </footer>
</body>
</html>
