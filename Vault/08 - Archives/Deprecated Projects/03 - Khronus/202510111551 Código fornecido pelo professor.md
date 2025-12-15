---
Date: 2025-10-11T15:22:00
Date - Mod:
tags:
  - temporary
  - programming
  - school
author: Colégio Estadual Professor Francisco Zardo
source: Google Drive
link:
---

# HTML - fornecido 



```
<html lang="pt-BR">

<head>

<meta charset="utf-8">

<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Khronus — Loja de informática</title>

<link rel="stylesheet" href="/home/antonabbac/Documentos/Projects/Khronus/src/styles/styles.css">

</head>

<body>

<header>

<p class="slogan">Fazendo seu tempo e dinheiro valerem a pena</p>

<nav>

<a href="#teclados">Teclados</a>

<a href="#mouses">Mouses</a>

<a href="#monitores">Monitores</a>

<a href="#placamae">Placas-mãe</a>

<a href="#placadev">Placas de vídeo</a>

<a href="#fontes">Fontes</a>

<a href="#armazenamento">Armazenamento</a>

</nav>

</header>

  

<main>

<h2>Produtos em Destaque</h2>

<table>

<tr>

<th>Imagem</th>

<th>Produto</th>

<th>Descrição</th>

<th>Preço</th>

</tr>

<tr id="teclados">

<td><img src="https://picsum.photos/seed/teclado1/120/80" alt="Teclado Mecânico"></td>

<td>Teclado Mecânico Gaming K-strike</td>

<td>Switches vermelhos, RGB, estrutura em alumínio</td>

<td>R$ 349,90</td>

</tr>

<tr id="mouses">

<td><img src="https://picsum.photos/seed/mouse1'/120/80" alt="Mouse Gamer"></td>

<td>Mouse Gamer RazerX Pro</td>

<td>Sensor 16000 DPI, iluminação presonalizável</td>

<td>R$ 199,90</td>

</tr>

<tr id="monitores">

<td><img src="https://picsum.photos/seed/monitor1/120/80" alt="Monitor 27"></td>

<td>Monitor 27" QHD 144Hz</td>

<td>2560x1440, painel IP, 144Hz</td>

<td>R$ 1.899,00</td>

</tr>

<tr id="placamae">

<td><img src="https://picsum.photos/seed/placamae1/120/80" alt="Placa-mãe"></td>

<td>Placa-mãe ATX prime x570</td>

<td>Soquete AM4, PCIe 4.0, suporte a memórias rápidas</td>

<td>R$ 1.299,00</td>

</tr>

<tr id="placadev">

<td><img src="https://picsum.photos/seed/placadev1/120/80" alt="Placa de vídeo"></td>

<td>VGA Turbo RTX 4070 Ti</td>

<td>Resfriamento avançado, ideal para 1440p</td>

<td>R$ 4.999,00</td>

</tr>

<tr id="fontes">

<td><img src="https://picsum.photos/seed/fonte1/120/80" alt="Fonte"></td>

<td>Fonte 650W Gold</td>

<td>Certificação 80 Plus Gold, cabos modulares</td>

<td>R$ 499,90</td>

</tr>

<tr id="Armazenamento">

<td><img src="https://picsum.photos/seed/ssd/120/80" alt="SSD"></td>

<td>SSD NVMe 1TB</td>

<td>Leitura até 3500MB/s, ótimo para jogos</td>

<td>R$ 649,00</td>

</tr>

</table>

</main>

  

<footer>

<p>© <span id="year"></span> LojaTech - Todos os direitos reservados</p>

</footer>

  

<script>

document.getElementById('year').textContent = new Date().getFullYear();

</script>

</body>

</html>
```

# CSS


```
/* style.css — LojaTech simples */

  

body {

font-family: Arial, sans-serif;

background-color: #f4f4f9;

margin: 0;

padding: 0;

text-align: center;

  
  

}

  

header {

background-color: #1e293b;

color: #fff;

padding: 20px;

  

}

  

header h1 {

margin: 0;

}

  

.slogan {

font-size: 14px;

color: #cdb5e1;

  

}

  

nav {

margin-top: 10px;

}

  

nav a {

color: #38bdf8;

text-decoration: none;

margin: 0 8px;

  

}

  

nav a:hover {

text-decoration: underline;

}

  

main {

margin: 20px auto;

width: 90%;

max-width: 1000px;

}

  

h2 {

color:#1e293b;

}

  

table {

width: 100%;

border-collapse: collapse;

background: #fff;

margin: 20px auto;

box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);

}

  

table th, table td {

border: 1px solid #ddd;

padding: 10px;

text-align: center;

}

  

table th {

background-color: #0ea5e9;

color:#fff;

}

  

table img {

border-radius: 6px;

}

  

footer {

background-color: #1e293b;

color: #cdb5e1;

padding: 10px;

margin-top: 20px;

}

```