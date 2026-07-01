# nosso-cantinho
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Thalison ❤️ Ellen</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Great+Vibes&display=swap" rel="stylesheet">

<link rel="stylesheet" href="style.css">
</head>

<body>

<div id="hearts"></div>

<section class="hero">

<h1>Thalison ❤️ Ellen</h1>

<p>Desde 12 de Abril de 2026</p>

<a href="#historia" class="btn">
Entrar no nosso cantinho
</a>

</section>

<section id="historia">

<h2>Você é meu lugar favorito ❤️</h2>

<p>
Desde que você entrou na minha vida,
tudo ficou mais bonito.

Obrigado por cada sorriso,
cada abraço
e cada momento ao seu lado.
</p>

</section>

<section class="contador">

<h2>Estamos juntos há</h2>

<div id="tempo"></div>

</section>

<section>

<h2>Nossas Memórias 📸</h2>

<div class="galeria">

<img src="imagens/foto1.jpg">

<img src="imagens/foto2.jpg">

<img src="imagens/foto3.jpg">

<img src="imagens/foto4.jpg">

<img src="imagens/foto5.jpg">

<img src="imagens/foto6.jpg">

<img src="imagens/foto7.jpg">

</div>

</section>

<section class="carta">

<h2>Para a minha Ellen ❤️</h2>

<p>

Meu amor,

Obrigado por cada momento que vivemos.

Você transformou minha vida de um jeito que palavras nunca vão conseguir explicar.

Espero que este seja apenas o começo da nossa história.

Eu escolheria você mil vezes.

E escolheria mais uma.

Te amo infinitamente.

❤️

— Thalison

</p>

</section>

<section class="musica">

<h2>Nossa música 🎵</h2>

<a class="btn"
href="https://youtu.be/QQKnT5t6w7Q"
target="_blank">

Ouvir "Te Vivo"

</a>

</section>

<footer>

<h2>

"Em qualquer lugar do mundo...

eu escolheria você."

❤️

</h2>

</footer>

<script src="script.js"></script>

</body>
</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
font-family:Poppins,sans-serif;
background:#050505;
color:white;
overflow-x:hidden;
}

section{
padding:90px 25px;
text-align:center;
}

.hero{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(180deg,#000,#111);
}

.hero h1{
font-family:"Great Vibes",cursive;
font-size:70px;
color:#ff4d6d;
}

.hero p{
font-size:22px;
margin:20px;
}

.btn{
display:inline-block;
margin-top:30px;
padding:15px 35px;
background:#ff4d6d;
color:white;
text-decoration:none;
border-radius:40px;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
}

h2{
margin-bottom:25px;
font-size:34px;
}

#tempo{
font-size:34px;
font-weight:bold;
color:#ff4d6d;
}

.galeria{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:40px;
}

.galeria img{
width:100%;
border-radius:20px;
transition:.4s;
box-shadow:0 0 25px rgba(255,255,255,.12);
}

.galeria img:hover{
transform:scale(1.05);
}

.carta{
max-width:900px;
margin:auto;
line-height:2;
font-size:20px;
}

footer{
padding:120px 30px;
text-align:center;
background:black;
}

footer h2{
font-family:"Great Vibes",cursive;
font-size:50px;
color:#ff4d6d;
}

.heart{
position:fixed;
top:-10px;
font-size:18px;
animation:fall linear forwards;
pointer-events:none;
}

@keyframes fall{

to{

transform:translateY(110vh);

opacity:0;

}

}