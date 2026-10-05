<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gymclass - Tienda de Suplementos</title>
    
    <link rel="stylesheet" href="estilos.css">
</head>
<body>

    
    <header>
        <div class="logo">
            💪 Gymclass
        </div>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#productos">Productos</a>
            <a href="#nosotros">Nosotros</a>
            <a href="#contacto">Contacto</a>
        </nav>
        <button class="carrito-bn" onclick="mostrarcarrito()">
            🛒 Carrito (<span id="cantidad-carrito">0</span>)
        </button>
    </header>

    <main>
        
        <section id="inicio" class="hero">
            <div class="hero-contenido">
                <h1>Encuentra los mejores suplementos que puedas desear</h1>
                <p>
                    Los mejores suplementos están disponibles en tu tienda favorita.
                </p>
                <a href="#productos" class="boton">
                    Ver productos
                </a>
            </div>
        </section>

        
        <section id="productos" class="productos-seccion">
            <h2>Nuestros productos</h2>
            <p class="descripcion">
                Elige los suplementos que tus músculos necesitan
            </p>

            
            <div class="busqueda">
                <input 
                    type="text" 
                    id="buscador" 
                    placeholder="Buscar producto...">
            </div>

            
            <div class="producto">
                <img src="https://farmacityar.vtexassets.com/arquivos/ids/275898-1600-auto?v=638877683379130000&width=1600&height=auto&aspect=true" alt="Creatina ENA">
                <h3>Creatina ENA</h3>
                <p>Creatina ENA, monohidratada y de la mejor y más alta calidad.</p>
                <span class="precio">Q. 300.00</span>
                <button onclick="agregarCarrito('Creatina ENA', 300)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://m.media-amazon.com/images/I/71mx0sYCEXL._AC_SY300_SX300_QL70_ML2_.jpg" alt="Proteína Whey">
                <h3>Proteína Whey</h3>
                <p>Proteína de la mejor y más alta calidad para desarrollo muscular.</p>
                <span class="precio">Q. 800.00</span>
                <button onclick="agregarCarrito('Proteína Whey', 800)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://i5.walmartimages.com/asr/5c0e069e-5144-4d30-805d-56303e3d543c.04be4f48499d7e9f27441f7db6d79c68.png?odnHeight=612&odnWidth=612&odnBg=FFFFFF" alt="Proteína CBUM">
                <h3>Proteína CBUM</h3>
                <p>Proteína de la calidad de un campeón.</p>
                <span class="precio">Q. 1,200.00</span>
                <button onclick="agregarCarrito('Proteína CBUM', 1200)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://http2.mlstatic.com/D_NQ_NP_2X_656627-MLM83741839270_042025-F.webp" alt="Creatina Ronnie Coleman">
                <h3>Ronnie Coleman</h3>
                <p>Nuestros proveedores han traído a casa la creatina del Olympia.</p>
                <span class="precio">Q. 400.00</span>
                <button onclick="agregarCarrito('Ronnie Coleman', 400)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://dojiw2m9tvv09.cloudfront.net/46246/product/X_psychotic-gold-orange2019.jpg?264&t=1790647532" alt="Pre-entreno Psychotic">
                <h3>Pre entreno Psychotic</h3>
                <p>Un pre entreno de alta intensidad para tus entrenamientos.</p>
                <span class="precio">Q. 400.00</span>
                <button onclick="agregarCarrito('Pre entreno Psychotic', 400)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://resources.sears.com.mx/medios-plazavip/t1/1719204641fruitjpg?scale=700&qlty=80" alt="Pre-entreno Hellboy">
                <h3>Hellboy</h3>
                <p>Para un entrenamiento de máxima exigencia.</p>
                <span class="precio">Q. 600.00</span>
                <button onclick="agregarCarrito('Pre-entreno Hellboy', 600)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://yaxa.co/_img/N5m056GnHpdciqL4esxzC4gbWdlXljLjl5s7x52cvL0/rs:fit:500:500:0/q:82/aHR0cHM6Ly9tLm1lZGlhLWFtYXpvbi5jb20vaW1hZ2VzL0kvNjF2ejA5YWdPQUwuX0FDX1NMMTUwMF8uanBn.webp" alt="Aminoácidos EAAS">
                <h3>Aminoácidos EAAS</h3>
                <p>Tu mejor opción para estimular de la mejor manera tus músculos.</p>
                <span class="precio">Q. 1,000.00</span>
                <button onclick="agregarCarrito('Aminoácidos EAAS', 1000)">
                    Agregar al carrito
                </button>
            </div>

            <div class="producto">
                <img src="https://www.health-shack.com/wp-content/uploads/2024/02/C4_Original_30serv_watermelon.jpg" alt="Pre-entreno C4">
                <h3>Pre-entreno C4</h3>
                <p>Sabor ponche de frutas, diseñado para darte energía explosiva.</p>
                <span class="precio">Q. 800.00</span>
                <button onclick="agregarCarrito('Pre-entreno C4', 800)">
                    Agregar al carrito
                </button>
            </div>
        </section>

        
        <section id="nosotros" class="nosotros">
            <h2>Sobre nosotros</h2>
            <p>
                En Gymclass buscamos darte lo que te mereces: amor propio y salud.
                Aquí encontrarás suplementos para crecer de una manera muy efectiva.
            </p>
            <p>
                Nuestro objetivo es ayudarte a encontrar el potencial que llevas dentro.
            </p>
        </section>

       
        <section id="contacto" class="contacto">
            <h2>Contáctanos</h2>
            <p>📍 Guatemala, Guatemala</p>
            <p>📞 Teléfono: 1234-5678</p>
            <p>✉️ Correo: suplestore@gmail.com</p>
        </section>
    </main>

    
    <footer> 
        <p><strong>Gymclass</strong></p>
        <p>© 2026 Todos los derechos reservados.</p>
    </footer>

    
    <div id="ventana-carrito" class="carrito">
        <div class="carrito-contenido">
            <span class="cerrar" onclick="cerrarCarrito()">&times;</span>
            <h2>Mi carrito</h2>

            <div id="lista-carrito">
                <p>Tu carrito está vacío.</p>
            </div>

            <h3>Total: Q. <span id="total-carrito">0.00</span></h3>

            <button onclick="finalizarCompra()">
                Finalizar Compra
            </button>
        </div>
    </div>

    
    <script src="script.js"></script>
</body>
</html>
