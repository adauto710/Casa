<html lang="pt br">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Adauto Silva</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>

  <Div>
    <nav>
      <ul class="center">
        <li>
          <a href="index.html">Sobre Mim</a>
        </li>
        <li>
          <a href="project.html">Projeto</a>
        </li>
        <li>
          <a href="contact.html">Contato</a>
        </li>
        <li>
          <a href="Parceiros.html">Parceiros</a>
        </li>
      </ul>
    </nav>
  </Div>

  <header>
    <Div class="center"><a href="Formação.html"><img src="./img/uma cachorra pitbull numa floresta.PNG"></img>
      </a>
      <img src="./img/Adauto.jpg"></img>

      <img src="./img/Navio.PNG"></img>

    </Div>
    <h1 class="center">Adauto Silva</h1>
    <h2 class="center">Programador Web</h2>
  </header>

  <main>
    <ul class="center">
      <section>
        <h3><a href="Sobre Mim.html">Sobre Mim</a></h3>
        <p>
          Devíamos ser ensinados a não esperar por inspiração para começar algo. Ação sempre gera inspiração.
          Inspiração raramente gera ação.
        </p>
      </section>
      <section>
        <h3><a href="Formação.html">Formação</a></h3>
        <p>
          Descubra quem é você, e seja essa pessoa. A sua alma foi colocada nesse mundo para ser isso, então
          viva essa verdade e todo resto virá.
      </section>
      <section>
        <h3><a href="contact.html">Cursos</a></h3>
        <p>
          Não existe nada de completamente errado no mundo, mesmo um relógio parado, consegue estar certo duas
          vezes por dia.
        </p>
      </section>
    </ul>
  </main>

  <footer>
    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer">
      <img src="./img/facebook-logo.svg"></img>
    </a>

    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer">
      <p>Facebook</p>
    </a>

    <a href="https://www.youtube.com/" target="_blank" rel="noopener noreferrer">
      <img src="./img/iconos.redes.sociales.youtube.png"></img>
    </a>

    <a href="https://www.youtube.com/" target="_blank" rel="noopener noreferrer">
      <p>You tube</p>
    </a>

    <a href="https://web.whatsapp.com/" target="_blank" rel="noopener noreferrer">
      <img src="./img/406px-WhatsApp_logo1.svg.png"></img>
    </a>

    <a href="https://web.whatsapp.com/" target="_blank" rel="noopener noreferrer">
      <p>Whatsapp</p>
    </a>
  </footer>
body {
    color: greenyellow;
    background-color: rgb(27, 4, 108);
    font-family: Arial, Helvetica, sans-serif;
}

ul li {
    list-style: none;
    padding: 10px;
    margin: 10px;
    background-color: rgb(63, 48, 103);
    color: rgb(245, 248, 240);
    border-radius: 10px;
    display: flex;
bottom: left;
    justify-content: space-between;
}
ul {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 20px;
    padding: 20px;
    background-color: rgb(63, 48, 103);
    border-radius: 10px;
    border: 2px solid rgb(233, 28, 28);

}

section h3 {
    color: tomato;
}

header img {
    width: 300px;
    margin: 40px;
    height: 200px;
    border-radius: 1%;
    border: 2px solid rgb(233, 28, 28)
}

.center {
    text-align: center;
    margin: 20px;
}

h1 {
    color: rgb(202, 14, 14);
}

footer img {
    width: 60px;
    height: 80px;
    padding: 8px;
}

footer {
    display: flex;
    justify-content: center;
    margin: 20px;
}

footer a {
    margin: 20px;
    text-align: center;
}

section p {
    margin: 20px;
    text-align: center;
    display: flex;
}

footer p {
    margin: 20px;
    text-align: center;
    display: flex;
}

.container {
    padding: 8px 100px;
}

nav a:hover {
    color: red;
}

section a:hover {
    color: rgb(65, 24, 231);
}




  <body>
    <h1>Exemplo de Vídeo em HTML</h1>

    <video width="640" height="360" controls>
      <source src="formatura.mp4" type="video/mp4">
      Seu navegador não suporta o elemento de vídeo.
    </video>

  </body>

</body>

</html>
