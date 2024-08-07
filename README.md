
# Felipe Macedo dos Santos

### Minhas redes
<a href="https://www.linkedin.com/in/felipe-macedo-dos-santos-37264a1b5/">
  <img src="https://img.freepik.com/vetores-premium/logotipo-linkedin_578229-227.jpg" alt="Perfil do LinkedIn de Felipe Macedo" width="30" height="30">
</a>
<a href="https://github.com/fmacedosantos/">
  <img src="https://play-lh.googleusercontent.com/PCpXdqvUWfCW1mXhH1Y_98yBpgsWxuTSTofy3NGMo9yBTATDyzVkqU580bfSln50bFU=w240-h480-rw" alt="Perfil do GitHub de Felipe Macedo" width="30" height="30">
</a>

<div id="dark-mode-toggle">
  <button onclick="toggleDarkMode()">Modo Escuro</button>
</div>

>**Conheça a minha história:**

## Sobre mim
Minha jornada na programação começou em 2020, com cursos online em plataformas como **[Curso em vídeo](https://www.cursoemvideo.com/)** e **[Alura](https://www.alura.com.br/)**. Em seguida, busquei uma experiência mais prática e me matriculei no curso técnico em Desenvolvimento de Sistemas no **[SENAI](https://sp.senai.br/unidade/campinaszerbini/)**.

Durante o curso técnico, tive a oportunidade de:
* Trabalhar em equipe em diversos projetos, utilizando a metodologia ágil _Scrum_.
* Desenvolver habilidades como **Liderança**, **Trabalho em Equipe**, **Gestão de Tempo** e **Comunicação**.
* Gerenciar times de desenvolvimento.

Atualmente, estou no último semestre do técnico e cursando Ciência da Computação na **[Wyden](https://www.wyden.com.br/)**. Essa combinação me permite aprofundar meus conhecimentos em engenharia de software e as minhas soft skills.

## Formação Acadêmica
* SENAI: **Técnico em Desenvolvimento de Sistemas** (4/4)
* Wyden: **Ciência da Computação** (2/8)

## Portfólio 

#### **Mobile**
<ul>
    <li><a href="https://github.com/fmacedosantos/tickUpMobile">TickUp (Android Studio)</a></li>
    <li><a href="https://github.com/fmacedosantos/mobile-orgs-cesta">Cesta Virtual (React Native)</a></li>
    <li><a href="https://github.com/fmacedosantos/green-lantern">Lanterna Verde (React Native - TS)</a></li>
</ul>

#### **Front-end**
<ul>
    <li><a href="https://github.com/GustavoGuimaraes01/TickUp">TickUp</a></li>
    <li><a href="https://github.com/fmacedosantos/alura_space">Alura Space</a></li>
</ul>

#### **Back-end**
<ul>
  <li><a href="https://github.com/fmacedosantos/tickUpAPI">TickUp: API (ASP.NET)</a></li>
</ul>

#### **Desktop**
<ul>
    <li><a href="https://github.com/fmacedosantos/AdvocateLinkDesktop">AdvocateLink (Java)</a></li>
    <li><a href="https://github.com/fmacedosantos/AquaZen">AquaZen (Java)</a></li>
    <li><a href="https://github.com/fmacedosantos/sistema_bancario">Sistema bancário (Python)</a></li>
    <li><a href="https://github.com/fmacedosantos/vetorAleatorioC">Vetor aleatório (C)</a></li>
</ul>



<script>
function toggleDarkMode() {
  var body = document.body;
  var button = document.querySelector("#dark-mode-toggle button");

  body.classList.toggle("dark-mode");

  if (body.classList.contains("dark-mode")) {
    button.textContent = "Modo Claro";
  } else {
    button.textContent = "Modo Escuro";
  }

  saveModeState();
}

// cria uma função para salvar o estado do modo no localStorage
function saveModeState() {
    var body = document.body;
    if (body.classList.contains("dark-mode")) {
        localStorage.setItem("darkMode", "enabled");
    } else {
        localStorage.setItem("darkMode", "disabled");
    }
}

// carrega o estado do modo salvo no localStorage ao carregar a página
window.onload = function() {
    var darkModeState = localStorage.getItem("darkMode");
    var body = document.body;
    if (darkModeState === "enabled") {
        body.classList.add("dark-mode");
    } else {
        body.classList.remove("dark-mode");
    }
};

// adiciona um evento para salvar o estado do modo ao fechar a página
window.onbeforeunload = saveModeState;
</script>

<style>
body {
    transition: background-color 0.4s ease;
}

div {
  margin-bottom: 20px;
}

.light-mode {
    background-color: #ffffff;
    color: #333333;
}

.dark-mode {
    background-color: #333333;
    color: #ffffff;
}

  .dark-mode a {
  color: #f0a500; 
}
</style>
