<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EMPRENDE IA | Innovación para el Perú</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f5f8ff;
color:#222;
overflow-x:hidden;
}

header{
background:linear-gradient(135deg,#003b95,#00b96b);
color:white;
padding:120px 10%;
text-align:center;
}

header h1{
font-size:4rem;
margin-bottom:20px;
}

header p{
font-size:1.2rem;
max-width:900px;
margin:auto;
line-height:1.8;
}

.btn{
display:inline-block;
margin-top:30px;
padding:15px 35px;
background:white;
color:#003b95;
font-weight:bold;
border-radius:40px;
text-decoration:none;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
}

nav{
position:sticky;
top:0;
background:white;
padding:15px;
display:flex;
justify-content:center;
gap:25px;
z-index:1000;
box-shadow:0 2px 10px rgba(0,0,0,.1);
}

nav a{
text-decoration:none;
color:#003b95;
font-weight:600;
}

section{
padding:80px 10%;
}

.titulo{
font-size:2.5rem;
color:#003b95;
text-align:center;
margin-bottom:40px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
border-radius:15px;
margin-bottom:15px;
}

.card h3{
color:#00a86b;
margin-bottom:10px;
}

.mision{
background:white;
padding:40px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
line-height:1.8;
}

.estadisticas{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.numero{
font-size:3rem;
font-weight:800;
color:#00b96b;
}

.contador{
background:white;
padding:30px;
text-align:center;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.generador{
background:white;
padding:30px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

select,button{
width:100%;
padding:15px;
margin-top:15px;
border:none;
border-radius:10px;
font-size:1rem;
}

button{
background:#003b95;
color:white;
cursor:pointer;
}

.resultado{
margin-top:25px;
padding:20px;
background:#eef7ff;
border-radius:15px;
line-height:1.8;
}

.mapa{
text-align:center;
}

.mapa img{
max-width:500px;
width:100%;
}

footer{
background:#003b95;
color:white;
padding:40px;
text-align:center;
}

.curso{
background:white;
padding:25px;
border-radius:20px;
margin-bottom:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.banner{
background:linear-gradient(135deg,#00b96b,#0091ff);
padding:60px;
border-radius:25px;
color:white;
text-align:center;
}

</style>
</head>

<body>

<nav>
<a href="#nosotros">Nosotros</a>
<a href="#objetivos">Objetivos</a>
<a href="#ideas">Generador IA</a>
<a href="#regiones">Regiones</a>
<a href="#casos">Proyectos</a>
<a href="#academia">Academia</a>
</nav>

<header>

<h1>🚀 EMPRENDE IA</h1>

<p>
La primera plataforma educativa inteligente creada para inspirar a estudiantes
de todas las regiones del Perú a convertir sus ideas en proyectos innovadores,
sostenibles y con impacto social. Nuestro propósito es democratizar la innovación
y brindar oportunidades a jóvenes de comunidades rurales, urbanas y amazónicas.
</p>

<a href="#ideas" class="btn">Generar Idea Innovadora</a>

</header>

<section id="nosotros">

<h2 class="titulo">¿Por qué nace Emprende IA?</h2>

<div class="mision">

<p>
Miles de estudiantes peruanos poseen creatividad, talento y deseos de transformar
sus comunidades. Sin embargo, muchos no cuentan con acceso a herramientas,
orientación o recursos para convertir sus ideas en proyectos reales.
</p>

<br>

<p>
Emprende IA surge como una solución tecnológica educativa que conecta la innovación,
la creatividad y el emprendimiento con las necesidades reales de las regiones del Perú.
La plataforma utiliza herramientas digitales para ayudar a los estudiantes a identificar
problemas, generar ideas, diseñar soluciones y presentar proyectos de impacto.
</p>

</div>

</section>

<section id="objetivos">

<h2 class="titulo">Objetivos del Proyecto</h2>

<div class="grid">

<div class="card">
<h3>💡 Creatividad</h3>
<p>Fomentar el pensamiento creativo para generar soluciones innovadoras.</p>
</div>

<div class="card">
<h3>🚀 Innovación</h3>
<p>Promover proyectos tecnológicos, ecológicos y sociales.</p>
</div>

<div class="card">
<h3>🌎 Inclusión</h3>
<p>Reducir las brechas educativas en regiones con menos recursos.</p>
</div>

<div class="card">
<h3>🤝 Impacto Social</h3>
<p>Desarrollar proyectos que beneficien directamente a la comunidad.</p>
</div>

</div>

</section>

<section>

<h2 class="titulo">Impacto Esperado</h2>

<div class="estadisticas">

<div class="contador">
<div class="numero">25</div>
<p>Regiones del Perú</p>
</div>

<div class="contador">
<div class="numero">1000+</div>
<p>Ideas Innovadoras</p>
</div>

<div class="contador">
<div class="numero">500+</div>
<p>Escuelas Beneficiadas</p>
</div>

<div class="contador">
<div class="numero">10000+</div>
<p>Estudiantes Alcanzados</p>
</div>

</div>

</section>

<section id="ideas">

<h2 class="titulo">🤖 Generador Inteligente de Ideas</h2>

<div class="generador">

<select id="categoria">

<option value="">Seleccione una categoría</option>
<option>Medio Ambiente</option>
<option>Agricultura</option>
<option>Tecnología</option>
<option>Turismo</option>
<option>Educación</option>
<option>Salud</option>

</select>

<button onclick="generarIdea()">Generar Proyecto</button>

<div class="resultado" id="resultado">
Aquí aparecerá tu proyecto innovador.
</div>

</div>

</section>

<section id="regiones">

<h2 class="titulo">🗺️ Regiones del Perú</h2>

<div class="mapa">

<img src="https://upload.wikimedia.org/wikipedia/commons/0/01/Peru_location_map.svg">

<p>
Emprende IA busca llegar a todas las regiones del Perú fortaleciendo la innovación,
la creatividad y el emprendimiento juvenil.
</p>

</div>

</section>

<section id="casos">

<h2 class="titulo">🏆 Proyectos Destacados</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1464226184884-fa280b87c399">
<h3>Huertos Inteligentes</h3>
<p>
Sistema de riego automatizado para mejorar la producción agrícola escolar.
</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1516321318423-f06f85e504b3">
<h3>Aula Virtual Rural</h3>
<p>
Plataforma educativa para comunidades alejadas.
</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1521791136064-7986c2920216">
<h3>Turismo Comunitario</h3>
<p>
Promoción digital de atractivos turísticos locales.
</p>
</div>

</div>

</section>

<section id="academia">

<h2 class="titulo">📚 Academia Emprende IA</h2>

<div class="curso">
<h3>Design Thinking</h3>
<p>
Metodología para identificar problemas y crear soluciones centradas en las personas.
</p>
</div>

<div class="curso">
<h3>Modelo Canvas</h3>
<p>
Herramienta para diseñar modelos de negocio de manera visual y estratégica.
</p>
</div>

<div class="curso">
<h3>Marketing Digital</h3>
<p>
Aprende a promocionar proyectos mediante redes sociales y plataformas digitales.
</p>
</div>

<div class="curso">
<h3>Finanzas Básicas</h3>
<p>
Conoce cómo administrar recursos y elaborar presupuestos.
</p>
</div>

<div class="curso">
<h3>Pitch de Negocios</h3>
<p>
Aprende a presentar proyectos ante jurados e inversionistas.
</p>
</div>

</section>

<section>

<div class="banner">

<h2>🌟 Nuestro Mensaje</h2>

<br>

<p>
"Las grandes transformaciones no comienzan con millones de soles; comienzan con una idea.
Emprende IA existe para ayudar a que cada joven peruano descubra que puede convertirse en
un agente de cambio para su comunidad y para el país."
</p>

</div>

</section>

<footer>

<h3>EMPRENDE IA 2026</h3>

<p>
Innovación • Creatividad • Emprendimiento • Impacto Social
</p>

</footer>

<script>

function generarIdea(){

let categoria=document.getElementById("categoria").value;
let resultado=document.getElementById("resultado");

let ideas={

"Medio Ambiente":`
🌱 ECO SMART PERÚ

Problema:
Contaminación por residuos.

Solución:
Estaciones inteligentes de reciclaje con QR.

Impacto:
Reducción de residuos y educación ambiental.

Aliados:
Municipalidades y MINAM.

ODS:
Acción por el Clima.
`,

"Agricultura":`
🌾 AGROTECH ESCOLAR

Problema:
Baja productividad agrícola.

Solución:
Sensores de humedad para optimizar riego.

Impacto:
Mayor producción y ahorro de agua.

Aliados:
Ministerio de Agricultura.
`,

"Tecnología":`
🤖 APP COMUNIDAD DIGITAL

Problema:
Escaso acceso a información.

Solución:
Aplicación móvil para servicios comunitarios.

Impacto:
Conectividad y acceso al conocimiento.
`,

"Turismo":`
🏔️ TURISMO DIGITAL PERÚ

Problema:
Poca promoción local.

Solución:
Plataforma de rutas turísticas digitales.

Impacto:
Mayor ingreso económico local.
`,

"Educación":`
📚 AULA IA

Problema:
Dificultades de aprendizaje.

Solución:
Tutor virtual con inteligencia artificial.

Impacto:
Mejora del rendimiento académico.
`,

"Salud":`
❤️ SALUD CERCA DE TI

Problema:
Falta de orientación preventiva.

Solución:
Aplicación de seguimiento y consejos de salud.

Impacto:
Prevención y bienestar comunitario.
`

};

resultado.innerHTML=ideas[categoria] || "Seleccione una categoría.";

}

</script>

</body>
</html>
