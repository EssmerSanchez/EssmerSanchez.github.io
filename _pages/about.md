---
layout: about
title: about
permalink: /
subtitle: Sanchez.Essmer@gmail.com          (347) 313-8530 # <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.
email: 

profile:
  align: right
  image: ezz.png
  image_circular: false # crops the image to make it circular
  more_info: # >
  # <p>(718) 791-3656</p>
  # <p>Queens NY</p>
  # <p>Your City, State 12345</p>

news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<html>
<head>
<style>
.tabs {
  overflow: hidden;
  background: #f1f1f1;
  font-family: Arial;
}
.tabs a {
  float: left;
  display: block;
  color: #b509ac;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  transition: 0.3s;
}
.tabs a:hover {
  background-color: #ddd;
}
.tabcontent {
  display: none;
  padding: 6px 12px;
  border-top: none;
}
</style>
</head>
<body>

<div class="tabs">
  <a href="#" class="tablink" onclick="openSection(event, 'English')">English</a>
  <a href="#" class="tablink" onclick="openSection(event, 'Español')">Español</a>
  <a href="#" class="tablink" onclick="openSection(event, 'Polski')">Polski</a>
</div>

<div id="English" class="tabcontent">
  <h3>My Story</h3>
  <p> Hello, my name is Essmer Sanchez. I am of Mexican decent with a mixed family from Poland, Ecuador and Colombia. I grew up in Queens surrounded by a variety of cultures that have given me a glimps of what the world has to offer.</p>
  <p> I hold a degree in Computer Science and a certification as an Adult English instructor from The Literacy Assistance Center of New York.Currently I am part of a construction company startup as a Client Relations and Technology Administrator.</p>
  <p>My goal is to work in the tech industry. As I make progress on my journey, I want to give back to my community by teaching English and technology classes, offering school tutoring, and providing PC repair services.</p>
  <p> I would love to connect with you! Feel free to contact me through email or business phone number listed above.</p>
</div>

<div id="Español" class="tabcontent">
  <h3>Mi historia</h3>
  <p> Hola, mi nombre es Essmer Sanchez. Soy de ascendencia mexicana con una familia mixta de Polonia, Ecuador y Colombia. Crecí en Queens, rodeado de una variedad de culturas que me han dado un vistazo de lo que el mundo tiene para ofrecer.</p>
  <p>Tengo un título en Ciencias de la Computación y una certificación como instructor de inglés para adultos del Literacy Assistance Center de Nueva York. Actualmente, soy parte de una empresa emergente de construcción como Administrador de Relaciones con Clientes y Tecnología.</p>
  <p>Mi objetivo es trabajar en la industria tecnológica. A medida que avanzo en mi camino, quiero retribuir a mi comunidad enseñando clases de inglés y tecnología, ofreciendo tutoría escolar y proporcionando servicios de reparación de computadoras.</p>
  <p>¡Me encantaría conectarme contigo! No dudes en contactarme a través del correo electrónico o del número de teléfono comercial que aparece arriba.</p>
</div>

<div id="Polski" class="tabcontent">
  <h3>Moja historia</h3>
  <p>Cześć, nazywam się Essmer Sanchez. Jestem pochodzenia meksykańskiego, a moja rodzina jest mieszanką narodowości z Polski, Ekwadoru i Kolumbii. Dorastałem w Queens, otoczony różnorodnymi kulturami, które dały mi wgląd w to, co świat ma do zaoferowania.</p>
  <p>Mam dyplom z Informatyki oraz certyfikat instruktora języka angielskiego dla dorosłych z Literacy Assistance Center w Nowym Jorku. Obecnie jestem częścią startupu budowlanego jako Administrator Relacji z Klientami i Technologii.</p>
  <p>Moim celem jest praca w branży technologicznej. W miarę postępów na mojej drodze, chcę odwdzięczyć się mojej społeczności poprzez nauczanie języka angielskiego i technologii, oferowanie korepetycji szkolnych oraz świadczenie usług naprawy komputerów.</p>
  <p>Chciałbym się z Tobą skontaktować! Nie wahaj się skontaktować ze mną przez e-mail lub numer telefonu biznesowego podany powyżej.</p>
</div>

<script>
function openSection(evt, sectionName) {
  var section = document.getElementById(sectionName);
  var tablinks = document.getElementsByClassName("tablink");
  for (var i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  if (section.style.display === "block") {
    section.style.display = "none";
  } else {
    var tabcontent = document.getElementsByClassName("tabcontent");
    for (var i = 0; i < tabcontent.length; i++) {
      tabcontent[i].style.display = "none";
    }
    section.style.display = "block";
    evt.currentTarget.className += " active";
  }
}
</script>

</body>
</html>

