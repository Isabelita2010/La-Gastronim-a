# La-Gastronim-a
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <title>La Gastronomía</title>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
  <style>
    /* Estilos generales */
    body {
      background-color: #fff2cc;
      font-family: 'Lato', sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Encabezado */
    header {
      text-align: center;
      background-color: #ffd7b3;
      padding: 20px;
      box-sizing: border-box;
      position: relative;
    }

    .titulo {
      font-size: 36px;
      color: #ff3737;
      margin-bottom: 10px;
      font-family: 'Playfair Display', serif;
    }

    /* Navegación */
    nav {
      background-color: #ff9900;
      height: 50px;
      display: flex;
      align-items: center;
      justify-content: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
    }

    nav ul li {
      margin: 0 20px;
    }

    nav ul li a {
      color: #fff2cc;
      font-weight: bold;
      font-size: 18px;
      font-family: 'Montserrat', sans-serif;
    }

    nav ul li a:hover {
      color: #ff3737;
      text-decoration: underline;
    }

    /* Secciones */
    #recetas, #informacion, #arte-de-cocinar {
      background-color: #ffd7b3;
      padding: 20px;
      margin: 20px;
      border: 2px dashed #ff9900;
      border-radius: 10px;
      box-sizing: border-box;
    }

    #recetas h2, #informacion h2, #arte-de-cocinar h2 {
      font-family: 'Great Vibes', cursive;
    }

    /* Tabla */
    table {
      border-collapse: collapse;
      width: 90%;
      margin: 0 auto 40px auto;
      background-color: #fff2cc;
    }

    th {
      border: 1px solid #ff9900;
      padding: 8px;
      background-color: #ff3737;
      color: #ffff00;
      font-family: 'Open Sans', sans-serif;
    }

    td {
      border: 1px solid #ff9900;
      padding: 8px;
      background-color: #ffd7b3;
      font-family: 'Open Sans', sans-serif;
    }

    /* Pie de página */
    footer {
      text-align: center;
      padding: 10px;
      background-color: #ffd7b3;
      color: #333;
      border-top: 2px solid #ff9900;
      position: relative;
      bottom: 0;
      width: 100%;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Lato:wght@400;700&family=Montserrat:wght@400;700&family=Open+Sans:wght@400;700&family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="container-fluid">
    <h1 class="titulo">La Gastronomía</h1>
    <img src="https://images.app.goo.gl/6ZgF3P2HCZ8Cteer5.jpg" alt="Imagen de gastronomía" width="300" class="img-fluid">
  </header>

  <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top justify-content-center">
    <ul class="navbar-nav">
      <li class="nav-item"><a class="nav-link" href="#recetas">Recetas</a></li>
      <li class="nav-item"><a class="nav-link" href="#informacion">Información</a></li>
      <li class="nav-item"><a class="nav-link" href="#arte-de-cocinar">Arte de cocinar</a></li>
      <li class="nav-item"><a class="nav-link" href="#tabla">Tabla de Gastronomía</a></li>
    </ul>
  </nav>

  <div class="container">
    <section id="informacion" class="row mt-5">
      <h2 class="subtitulo">Descubre el Mundo de la Gastronomía</h2>
      <p>La gastronomía es un concepto utilizado para referirse al arte y la ciencia de la preparación y disfrute de los alimentos...</p>
      <p>La gastronomía es una disciplina que abarca la preparación, la presentación y el disfrute de los alimentos. Es una forma de arte que combina la creatividad, la técnica y la pasión por la comida.</p>
      <button class="btn btn-primary" onclick="location.href='https://es.wikipedia.org/wiki/Gastronom%C3%ADa'">Más información</button>
    </section>

    <section id="recetas" class="row mt-5">
      <h2 class="subtitulo">Recetas</h2>
      <p>Aquí te presento algunas recetas deliciosas:</p>
      <ul>
        <li>Receta 1: <a href="https://www.recetasgratis.net/Receta-de-pollo-al-curry/16741.aspx">Pollo al curry</a></li>
        <li>Receta 2: <a href="https://www.recetasgratis.net/Receta-de-tortilla-de-espinacas/16855.aspx">Tortilla de espinacas</a></li>
        <li>Receta 3: <a href="https://www.recetasgratis.net/Receta-de-arroz-con-mariscos/16923.aspx">Arroz con mariscos</a></li>
      </ul>
    </section>

    <section id="arte-de-cocinar" class="row mt-5">
      <h2 class="subtitulo">Arte de cocinar</h2>
      <p>Aquí te presento algunas técnicas y consejos para mejorar tus habilidades culinarias:</p>
      <ul>
        <li>Técnica 1: <a href="https://www.cocinavital.com/tecnicas-de-coccion/coccion-al- vapor/">Cocción al vapor</a></li>
        <li>Técnica 2: <a href="https://www.cocinavital.com/tecnicas-de-coccion/sofrito/">Sofrito</a></li>
        <li>Técnica 3: <a href="https://www.cocinavital.com/tecnicas-de-coccion/horneado/">Horneado</a></li>
      </ul>
    </section>

    <h2 class="subtitulo" style="text-align: center;" id="tabla">Tabla de Gastronomía</h2>
    <table class="table table-striped">
      <tr>
        <th>Nombre del Plato</th>
        <th>Descripción</th>
        <th>País de Origen</th>
        <th>Tipo de Cocina</th>
      </tr>
      <tr>
        <td>Pizza</td>
        <td>Plato italiano consistente en una base de masa y toppings</td>
        <td>Italia</td>
        <td>Cocina italiana</td>
      </tr>
      <tr>
        <td>Sushi</td>
        <td>Plato japonés consistente en arroz y pescado crudo</td>
        <td>Japón</td>
        <td>Cocina japonesa</td>
      </tr>
      <tr>
        <td>Tacos al pastor</td>
        <td>Tacos mexicanos con carne marinada y piña</td>
        <td>México</td>
        <td>Cocina mexicana</td>
      </tr>
      <tr>
        <td>Feijoada</td>
        <td>Estofado brasileño hecho con frijoles negros</td>
        <td>Brasil</td>
        <td>Cocina brasileña</td>
      </tr>
    </table>
  </div>

  <aside class="bg-light border-left border-success p-3 mt-3">
    <h3 class="autor">Autor</h3>
    <p>Isabela Valencia Zapata</p>
    <p>Correo electrónico: <a href="mailto:valenciazapataisabela@gmail.com">valenciazapataisabela@gmail.com</a></p>
    <p>Teléfono: 3106125531</p>
  </aside>

  <footer class="bg-light text-center p-3 mt-3">
    <p>&copy; 2025 Isabela Valencia Zapata</p>
  </footer>
</body>
</html>
