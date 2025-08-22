<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catálogo Lencería Fra y Mar</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ffb6c1, #ff69b4);
    }
    header {
      text-align: center;
      padding: 1rem;
      background: #fff0f6;
      border-bottom: 3px solid #ff69b4;
    }
    header img {
      max-height: 100px;
    }
    nav {
      text-align: center;
      margin: 1rem 0;
    }
    nav button {
      margin: 0 0.5rem;
      padding: 0.5rem 1rem;
      border: none;
      background: #ff69b4;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
    }
    nav button:hover {
      background: #ff1493;
    }
    .seccion {
      display: none;
      padding: 1rem;
    }
    .seccion.active {
      display: block;
    }
    .marca {
      text-align: center;
      margin: 2rem 0 1rem;
    }
    .marca img {
      max-height: 60px;
    }
    .catalogo {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .producto {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      padding: 1rem;
      width: 180px;
      text-align: center;
    }
    .producto img {
      max-width: 100%;
      border-radius: 8px;
    }
    .producto h3 {
      margin: 0.5rem 0;
      font-size: 1rem;
    }
    .producto p {
      margin: 0.25rem 0;
      font-weight: bold;
    }
    .producto a {
      display: inline-block;
      margin-top: 0.5rem;
      padding: 0.3rem 0.6rem;
      background: #ff69b4;
      color: white;
      text-decoration: none;
      border-radius: 4px;
      font-size: 0.9rem;
    }
    .producto a:hover {
      background: #ff1493;
    }
  </style>
  <script>
    function mostrarSeccion(id) {
      document.querySelectorAll('.seccion').forEach(sec => sec.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</head>
<body>
  <header>
    <img src="imagenes/logo_negocio.png" alt="Lencería Fra y Mar">
    <h1>Catálogo Fra y Mar</h1>
  </header>

  <nav>
    <button onclick="mostrarSeccion('boxer')">Boxer</button>
    <button onclick="mostrarSeccion('medias')">Medias</button>
    <button onclick="mostrarSeccion('conjuntos')">Conjuntos</button>
  </nav>

  <!-- Sección BOXER -->
  <div class="seccion active" id="boxer">
    <h2 style="text-align:center;">Boxer</h2>

    <!-- Marca BARAK -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/Captura.PNG" alt="Barak">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Barak.jpg" alt="Boxer Barak">
        <h3>Boxer Barak Hombre</h3>
        <p>$1500</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Barak juvenil.png" alt="Boxer Barak">
        <h3>Boxer Barak Juvenil</h3>
        <p>$1500</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Barak niño.png" alt="Boxer Barak">
        <h3>Boxer Barak Niño</h3>
        <p>$1500</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>


    </section>

    <!-- Marca CAPICUA -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/Logo capicua.PNG" alt="Capicua">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Capicua liso.jpg" alt="Boxer Capicua">
        <h3>Boxer Capicua Liso</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Capicua seda fria.png" alt="Boxer Capicua">
        <h3>Boxer Seda Fria</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

    <!-- Marca DUFOUR -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/Logo Dufour.png" alt="Dufour">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Dufour 12056.jpg" alt="Boxer Dufour">
        <h3>Boxer Dufour Art.12056 </h3>
        <p>$56000</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Dufour 12060.jpg" alt="Boxer Dufour">
        <h3>Boxer Dufour Art.12052 </h3>
        <p>$56000</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

       <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Dufour.jpg" alt="Boxer Dufour">
        <h3>Boxer Dufour Art.12050</h3>
        <p>$56000</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

         <div class="producto">
        <img src="Imagenes/Catalogo Boxer/dufour slip.jpg" alt="Boxer Dufour">
        <h3>Slip Duofour</h3>
        <p>$56000</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

    <!-- Marca LODY -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/logo_men_black.png" alt="Lody">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Lody estam.jpg" alt="Boxer Lody">
        <h3>Boxer Lody Estampado</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Lody liso.jpg" alt="Boxer Lody">
        <h3>Boxer Lody Liso</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

    <!-- Marca XY -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/D_NQ_NP_691807-MLA72671704665_112023-O.webp" alt="XY">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Xy Boxer.jpg" alt="Boxer XY">
        <h3>Boxer XY Liso</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Xy estamp.jpg" alt="Boxer XY">
        <h3>Boxer XY Estampado</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Xy slip.jpg" alt="Boxer XY">
        <h3>Slip XY S/Elastico</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

       <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Xy slip 2.jpg" alt="Boxer XY">
        <h3>Slip C/Elastico</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

     <!-- Marca ZORBA -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/D_NQ_NP_613273-MLA45656237216_042021-O.webp" alt="Zorba">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Zorba hombre.jpg" alt="Boxer Zorba">
        <h3>Boxer Hombre Zorba</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Zorba.jpg" alt="Boxer Zorba">
        <h3>Boxer Niño Zorba</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

     <!-- Marca SwORD -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/D_NQ_NP_613273-MLA45656237216_042021-O.webp" alt="Sword">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Sword hombre.png" alt="Boxer Sword">
        <h3>Boxer Sword Hombre</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Sword niño.png" alt="Boxer Sword">
        <h3>Boxer Sword Niño</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

     <!-- Marca UOMO -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/Logo Uomo.PNG" alt="UOMO">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Uomo.jpg" alt="Boxer Uomo">
        <h3>Boxer Uomo Estampados</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

     <!-- Marca ZANTINO -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/Logo zantino.PNG" alt="Zantino">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Zantino.jpg" alt="Boxer Zantino">
        <h3>Boxer Zantino Hombre</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Zantino niño.png" alt="Boxer Zantino">
        <h3>Boxer Zantino Niño</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

      <!-- Marca KOLPER -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/D_NQ_NP_755226-MLA53184440880_012023-O.webp" alt="Kolper">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Kolper.jpg" alt="Boxer Kolper">
        <h3>Slip Kolper</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

      <!-- Marca FULL TIME -->
    <div class="marca">
      <img src="Imagenes/Catalogo Boxer/D_NQ_NP_613273-MLA45656237216_042021-O.webp" alt="Full Time">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Boxer/Full time slip.png" alt="Boxer Full Time">
        <h3>Slip Full Time</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

  </div>

  <!-- Sección MEDIAS  -->
  <div class="seccion" id="medias">
    <h2 style="text-align:center;">Medias</h2>
    
        <!-- Marca Elemento -->
    <div class="marca">
      <img src="Imagenes/Catalogo Medias/" alt="Elemento">
    </div>
    <section class="catalogo">

      <div class="producto">
        <img src="Imagenes/Catalogo Medias/Elemento Soquete Liso.jpg" alt="Medias Elemento">
        <h3>Elemento Soq.Liso</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

      <div class="producto">
        <img src="Imagenes/Catalogo Medias/Elemento Soquete Rayado.jpg" alt="Medias Elemento">
        <h3>Elemento Soq.Rayado</h3>
        <p>$1700</p>
        <a href="https://wa.me/5491112345678" target="_blank">Consultar</a>
      </div>

    </section>

  </div>

  <!-- Sección CONJUNTOS (vacía de ejemplo) -->
  <div class="seccion" id="conjuntos">
    <h2 style="text-align:center;">Conjuntos</h2>
    <!-- Agregar marcas y productos igual que arriba -->
  </div>

</body>
</html>
