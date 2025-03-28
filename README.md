# torres-del-paine 

---

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Bazar de Tara | Artesanías Patagónicas</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Barra de Navegación -->
    <header>
        <div class="logo">
            <h1>El Bazar de Tara</h1>
            <p>Artesanías de la Patagonia · Torres del Paine</p>
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#sobre-nosotros">Nosotros</a></li>
                <li><a href="#turismo">Turismo</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
        <div class="menu-mobile">
            <i class="fas fa-bars"></i>
        </div>
    </header>

    <!-- Hero Section (Imagen de fondo de Torres del Paine) -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Artesanía Local en el Corazón de la Patagonia</h2>
            <p>Productos únicos hechos a mano con materiales de la región.</p>
            <a href="#productos" class="btn">Descubrir</a>
        </div>
    </section>

    <!-- Productos Destacados -->
    <section id="productos" class="productos">
        <h2><span>Nuestros Productos</span></h2>
        <div class="productos-grid">
            <div class="producto">
                <img src="https://images.unsplash.com/photo-1604176354204-9268737828e4?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Lana patagónica">
                <h3>Tejidos en Lana Patagónica</h3>
                <p class="precio">$24.990 CLP</p>
            </div>
            <div class="producto">
                <img src="https://images.unsplash.com/photo-1602143407151-7111542de6e8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Madera nativa">
                <h3>Tallas en Madera Nativa</h3>
                <p class="precio">$32.500 CLP</p>
            </div>
            <div class="producto">
                <img src="https://images.unsplash.com/photo-1583744946564-b52d01e2da64?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3¡Ah, perfecto! Aquí tienes el código completo para una página web de **"El Bazar de Tara" en Torres del Paine, Chile**, con diseño inspirado en la naturaleza patagónica, productos artesanales locales y secciones adaptadas al turismo.  

---

## **🌿 Página Web: "El Bazar de Tara" (Torres del Paine, Chile)**  
**Tecnologías usadas**:  
- **HTML5** (estructura semántica)  
- **CSS3** (estilos responsive + efectos visuales)  
- **JavaScript** (interacción básica)  

---

### **🔹 Código Completo** (3 archivos)  

#### **1. `index.html`** (Estructura principal con temática patagónica)  
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Bazar de Tara | Artesanías Patagónicas</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Barra de Navegación -->
    <header>
        <div class="logo">
            <h1>El Bazar de Tara</h1>
            <p>Artesanías de la Patagonia · Torres del Paine</p>
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#sobre-nosotros">Nosotros</a></li>
                <li><a href="#turismo">Turismo</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
        <div class="menu-mobile">
            <i class="fas fa-bars"></i>
        </div>
    </header>

    <!-- Hero Section (Imagen de fondo de Torres del Paine) -->
    <section id="inicio" class="hero">
        <div class="hero-content">
            <h2>Artesanía Local en el Corazón de la Patagonia</h2>
            <p>Productos únicos hechos a mano con materiales de la región.</p>
            <a href="#productos" class="btn">Descubrir</a>
        </div>
    </section>

    <!-- Productos Destacados -->
    <section id="productos" class="productos">
        <h2><span>Nuestros Productos</span></h2>
        <div class="productos-grid">
            <div class="producto">
                <img src="https://images.unsplash.com/photo-1604176354204-9268737828e4?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Lana patagónica">
                <h3>Tejidos en Lana Patagónica</h3>
                <p class="precio">$24.990 CLP</p>
            </div>
            <div class="producto">
                <img src="https://images.unsplash.com/photo-1602143407151-7111542de6e8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Madera nativa">
                <h3>Tallas en Madera Nativa</h3>
                <p class="precio">$32.500 CLP</p>
            </div>
            <div class="producto">
                <img src="https://images.unsplash.com/photo-1583744946564-b52d01e2da64?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3
