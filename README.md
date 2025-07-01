<!DOCTYPE html>
<html lang="pt-br" class="">
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Belleza&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Readme</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="cabecalho">
      <img src="./assets/cabecalho-projeto.png" />
    </div>
    <div class="texto-cabecalho">
      Este é um projeto de página de perfil pessoal, desenvolvido com o objetivo
      de praticar conceitos de HTML, CSS e JavaScript, além de aplicar
      conhecimentos sobre alternância de temas e responsividade.
    </div>
    <div class="titulo">FUNCIONALIDADES</div>
    <div class="texto">
      <ul>
        <li>Alternância entre modo claro e escuro</li>
        <li>Foto de perfil e bio de apresentação</li>
        <li>Links para redes sociais</li>
      </ul>
    </div>
    <div class="titulo">TECNOLOGIAS</div>
    <div class="texto">
      <a
        href="https://learn.microsoft.com/pt-br/cpp/mfc/html-basics?view=msvc-170"
        target="_blank"
        ><span class="badge">HTML</span></a
      >
      <a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS" target="_blank"
        ><span class="badge">CSS</span></a
      >
      <a
        href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript"
        target="_blank"
        ><span class="badge">JavaScript</span></a
      >
      <a href="https://docs.github.com/pt" target="_blank"
        ><span class="badge">Git e GitHub</span></a
      >
    </div>
    <div class="titulo">STATUS DO PROJETO</div>
    <div class="texto">
      Em desenvolvimento. Novas melhorias visuais e funcionalidades podem ser
      adicionadas em breve
    </div>
    <div class="titulo">PREVIEW</div>
    <div class="texto">
      <img class="img-preview" src="./assets/exemplo-projeto.png" />
    </div>
    <style>
        * {
  background-color: #e8d7cf;
  font-family: var(--font-family);
}
:root {
  --text-color-title: #a56e52;
  --text-color: #5c3927;
  --bg-url: url(./assets/cabecalho-projeto.png);
  --font-family: "Belleza", sans-serif;
  --switch-bg-url: url(./assets/MoonStars.svg);
  --highlight-color: rgba(255, 255, 255, 0.2);
  /*--stroke-color: rgba(255, 255, 255, 0.5);*/
  --surface-color: rgba(255, 255, 255, 0.1);
  --surface-color-hover: rgba(255, 255, 255, 0.05);
  align-items: center;
  justify-content: center;
  display: flex;
}
ul {
  margin: 0;
}
.cabecalho {
  background: var(--bg-url) no-repeat;
  border-radius: 10px;
}
img {
  border-radius: 10px;
}
.titulo {
  font-weight: 500;
  color: var(--text-color-title);
  font-size: 20px;
  padding-top: 20px;
  letter-spacing: 2px;
}
.texto {
  color: var(--text-color);
  padding-top: 5px;
}
.texto-cabecalho {
  color: var(--text-color);
  padding-top: 5px;
  text-align: center;
  max-width: 600px;
}
.img-preview {
  min-width: 150px;
}
.badge {
  display: inline-block;
  background-color: #f5eee9;
  color: var(--text-color);
  padding: 4px 8px;
  border-radius: 12px;
  margin: 4px 4px 0 0;
}
.badge:hover {
  background-color: #e4d1c4;
}
    </style>
  </body>
</html>