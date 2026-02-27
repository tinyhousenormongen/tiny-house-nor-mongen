<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tiny House Nor Mongen | Futrono</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#f2f5f3;color:#333;line-height:1.6}

header{
background:linear-gradient(rgba(0,0,0,0.45),rgba(0,0,0,0.45)),
url('https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:#fff;
padding:20px
}

header h1{font-size:3rem;margin-bottom:20px}
header p{font-size:1.2rem;max-width:700px;margin:auto}

.boton{
display:inline-block;
margin-top:30px;
padding:14px 30px;
background:#1f4d3a;
color:#fff;
text-decoration:none;
border-radius:30px;
font-weight:600;
transition:.3s
}

.boton:hover{background:#16382b}

nav{
position:fixed;
width:100%;
top:0;
background:rgba(0,0,0,0.6);
padding:15px;
text-align:center;
backdrop-filter:blur(6px);
z-index:1000
}

nav a{
color:#fff;
text-decoration:none;
margin:0 20px;
font-weight:500
}

section{
padding:90px 20px;
max-width:1200px;
margin:auto
}

.titulo{
text-align:center;
margin-bottom:50px
}

.titulo h2{
font-size:2.2rem;
color:#1f4d3a
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px
}

.card{
background:#fff;
padding:30px;
border-radius:20px;
box-shadow:0 15px 30px rgba(0,0,0,0.07);
transition:.3s
}

.card:hover{transform:translateY(-8px)}

.card h3{
margin-bottom:15px;
color:#1f4d3a
}

.galeria img{
width:100%;
border-radius:20px;
height:260px;
object-fit:cover
}

.contacto{
background:#1f4d3a;
color:#fff;
border-radius:30px;
padding:60px 30px;
text-align:center
}

footer{
background:#111;
color:#aaa;
text-align:center;
padding:30px;
margin-top:60px
}

@media(max-width:768px){
header h1{font-size:2.2rem}
}
</style>
</head>

<body>

<nav>
<a href="#inicio">Inicio</a>
<a href="#experiencia">Experiencia</a>
<a href="#galeria">Entorno</a>
<a href="#contacto">Contacto</a>
</nav>

<header id="inicio">
<div>
<h1>Tiny House Nor Mongen</h1>
<p>Refugio natural a orillas del Río Florín, en Futrono, Región de Los Ríos. Rodeada de cerros y naturaleza verde del sur de Chile.</p>
<a href="#contacto" class="boton">Próximamente Disponible</a>
</div>
</header>

<section id="experiencia">
<div class="titulo">
<h2>Conecta con la Naturaleza</h2>
</div>

<div class="grid">
<div class="card">
<h3>🌊 Sonido del Río</h3>
<p>Un entorno perfecto para descansar con el sonido natural del agua y el aire puro del sur.</p>
</div>

<div class="card">
<h3>🌲 Bosque Nativo</h3>
<p>Rodeado de paisajes verdes característicos de la Región de Los Ríos.</p>
</div>

<div class="card">
<h3>🌄 Desconexión Total</h3>
<p>Ideal para quienes buscan tranquilidad y contacto real con la naturaleza.</p>
</div>
</div>
</section>

<section id="galeria">
<div class="titulo">
<h2>Entorno Natural</h2>
</div>

<div class="grid galeria">
<img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1000&q=80">
<img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?auto=format&fit=crop&w=1000&q=80">
<img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=1000&q=80">
<img src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?auto=format&fit=crop&w=1000&q=80">
</div>
</section>

<section id="contacto">
<div class="contacto">
<h2>Próximamente Arriendos Disponibles</h2>
<p style="margin-top:20px;line-height:1.8">
📍 Sector Los Cerrillos, Futrono, Región de Los Ríos, Chile<br><br>
📲 WhatsApp: +56 9 1234 5678<br><br>
📧 contacto@tinynormongen.cl
</p>
</div>
</section>

<footer>
<p>© 2026 Tiny House Nor Mongen · Futrono · Región de Los Ríos · Chile</p>
</footer>

</body>
</html>
