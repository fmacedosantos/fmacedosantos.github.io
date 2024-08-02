
# Felipe Macedo dos Santos

<div id="networks">
        <h4>Minhas redes</h4>
        <a href="https://www.linkedin.com/in/felipe-macedo-dos-santos-37264a1b5/">
            <img src="https://img.freepik.com/vetores-premium/logotipo-linkedin_578229-227.jpg" alt="Perfil do LinkedIn de Felipe Macedo" width="30" height="30">
        </a>
        <a href="https://github.com/fmacedosantos/">
            <img src="https://play-lh.googleusercontent.com/PCpXdqvUWfCW1mXhH1Y_98yBpgsWxuTSTofy3NGMo9yBTATDyzVkqU580bfSln50bFU=w240-h480-rw" alt="Perfil do GitHub de Felipe Macedo" width="30" height="30">
        </a>
    </div>


<div id="dark-mode-toggle">
  <button onclick="toggleDarkMode()">Modo Escuro</button>
  <button onclick="changeLanguage()">Pt-br</button>
</div>

<blockquote id="story">
        <strong>Conheça a minha história</strong>
    </blockquote>

<h2>Sobre mim</h2>
    <p id="about-me">
        Minha jornada na programação começou em 2020, com cursos online em plataformas como <a href="https://www.cursoemvideo.com/">Curso em vídeo</a> e <a href="https://www.alura.com.br/">Alura</a>. Em seguida, busquei uma experiência mais prática e me matriculei no curso técnico em Desenvolvimento de Sistemas no <a href="https://sp.senai.br/unidade/campinaszerbini/">SENAI</a>.
    </p>
    <ul id="about-list">
        <li>Trabalhar em equipe em diversos projetos, utilizando a metodologia ágil Scrum.</li>
        <li>Desenvolver habilidades como <strong>Liderança</strong>, <strong>Trabalho em Equipe</strong>, <strong>Gestão de Tempo</strong> e <strong>Comunicação</strong>.</li>
        <li>Gerenciar times de desenvolvimento.</li>
    </ul>
    <p id="current-status">
        Atualmente, estou no último semestre do técnico e cursando Ciência da Computação na <a href="https://www.wyden.com.br/">Wyden</a>. Essa combinação me permite aprofundar meus conhecimentos em engenharia de software e as minhas soft skills.
    </p>

  <h2>Formação Acadêmica</h2>
  <ul id="education">
      <li>SENAI: <strong>Técnico em Desenvolvimento de Sistemas</strong> (4/4)</li>
      <li>Wyden: <strong>Ciência da Computação</strong> (2/8)</li>
  </ul>

<h2>Portfólio</h2>
    
  <h4>Mobile</h4>
  <ul id="mobile">
      <li><a href="https://github.com/fmacedosantos/tickUpMobile">TickUp (Android Studio)</a></li>
      <li><a href="https://github.com/fmacedosantos/mobile-orgs-cesta">Cesta Virtual (React Native)</a></li>
  </ul>
  
  <h4>Front-end</h4>
  <ul id="frontend">
      <li><a href="https://github.com/GustavoGuimaraes01/TickUp">TickUp</a></li>
      <li><a href="https://github.com/fmacedosantos/alura_space">Alura Space</a></li>
  </ul>
  
  <h4>Back-end</h4>
  <ul id="backend">
      <li><a href="https://github.com/fmacedosantos/tickUpAPI">TickUp: API (ASP.NET)</a></li>
  </ul>
  
  <h4>Desktop</h4>
  <ul id="desktop">
      <li><a href="https://github.com/fmacedosantos/AdvocateLinkDesktop">AdvocateLink (Java)</a></li>
      <li><a href="https://github.com/fmacedosantos/AquaZen">AquaZen (Java)</a></li>
      <li><a href="https://github.com/fmacedosantos/sistema_bancario">Sistema bancário (Python)</a></li>
      <li><a href="https://github.com/fmacedosantos/vetorAleatorioC">Vetor aleatório (C)</a></li>
  </ul>



    <script>
        const translations = {
            "pt-br": {
                "title": "Felipe Macedo dos Santos",
                "networks": "Minhas redes",
                "darkMode": "Modo Escuro",
                "lightMode": "Modo Claro",
                "languageButton": "Pt-br",
                "story": "Conheça a minha história:",
                "aboutMeTitle": "Sobre mim",
                "aboutMe": `Minha jornada na programação começou em 2020, com cursos online em plataformas como <a href="https://www.cursoemvideo.com/">Curso em vídeo</a> e <a href="https://www.alura.com.br/">Alura</a>. Em seguida, busquei uma experiência mais prática e me matriculei no curso técnico em Desenvolvimento de Sistemas no <a href="https://sp.senai.br/unidade/campinaszerbini/">SENAI</a>.`,
                "aboutList": [
                    "Trabalhar em equipe em diversos projetos, utilizando a metodologia ágil Scrum.",
                    "Desenvolver habilidades como <strong>Liderança</strong>, <strong>Trabalho em Equipe</strong>, <strong>Gestão de Tempo</strong> e <strong>Comunicação</strong>.",
                    "Gerenciar times de desenvolvimento."
                ],
                "currentStatus": `Atualmente, estou no último semestre do técnico e cursando Ciência da Computação na <a href="https://www.wyden.com.br/">Wyden</a>. Essa combinação me permite aprofundar meus conhecimentos em engenharia de software e as minhas soft skills.`,
                "educationTitle": "Formação Acadêmica",
                "education": [
                    "SENAI: <strong>Técnico em Desenvolvimento de Sistemas</strong> (4/4)",
                    "Wyden: <strong>Ciência da Computação</strong> (2/8)"
                ],
                "portfolioTitle": "Portfólio",
                "mobileTitle": "Mobile",
                "frontendTitle": "Front-end",
                "backendTitle": "Back-end",
                "desktopTitle": "Desktop"
            },
            "en": {
                "title": "Felipe Macedo dos Santos",
                "networks": "My networks",
                "darkMode": "Dark Mode",
                "lightMode": "Light Mode",
                "languageButton": "En",
                "story": "Learn my story:",
                "aboutMeTitle": "About me",
                "aboutMe": `My journey in programming began in 2020, with online courses on platforms like <a href="https://www.cursoemvideo.com/">Curso em vídeo</a> and <a href="https://www.alura.com.br/">Alura</a>. Then, I sought more practical experience and enrolled in the technical course in Systems Development at <a href="https://sp.senai.br/unidade/campinaszerbini/">SENAI</a>.`,
                "aboutList": [
                    "Working in teams on various projects, using the agile Scrum methodology.",
                    "Developing skills like <strong>Leadership</strong>, <strong>Teamwork</strong>, <strong>Time Management</strong>, and <strong>Communication</strong>.",
                    "Managing development teams."
                ],
                "currentStatus": `Currently, I am in the last semester of the technical course and studying Computer Science at <a href="https://www.wyden.com.br/">Wyden</a>. This combination allows me to deepen my knowledge in software engineering and my soft skills.`,
                "educationTitle": "Education",
                "education": [
                    "SENAI: <strong>Technical in Systems Development</strong> (4/4)",
                    "Wyden: <strong>Computer Science</strong> (2/8)"
                ],
                "portfolioTitle": "Portfolio",
                "mobileTitle": "Mobile",
                "frontendTitle": "Front-end",
                "backendTitle": "Back-end",
                "desktopTitle": "Desktop"
            }
        };

        function toggleDarkMode() {
            var body = document.body;
            var button = document.querySelector("#dark-mode-toggle button");

            body.classList.toggle("dark-mode");

            if (body.classList.contains("dark-mode")) {
                button.textContent = translations[currentLanguage].lightMode;
            } else {
                button.textContent = translations[currentLanguage].darkMode;
            }

            saveModeState();
        }

        function changeLanguage() {
            currentLanguage = currentLanguage === "pt-br" ? "en" : "pt-br";
            document.documentElement.lang = currentLanguage;

            document.title = translations[currentLanguage].title;
            document.querySelector("#networks h4").textContent = translations[currentLanguage].networks;
            document.querySelector("#dark-mode-toggle button").textContent = translations[currentLanguage].darkMode;
            document.querySelector("#dark-mode-toggle button:nth-child(2)").textContent = translations[currentLanguage].languageButton;
            document.querySelector("#story strong").textContent = translations[currentLanguage].story;
            document.querySelector("h2:nth-of-type(1)").textContent = translations[currentLanguage].aboutMeTitle;
            document.querySelector("#about-me").innerHTML = translations[currentLanguage].aboutMe;

            const aboutListItems = document.querySelectorAll("#about-list li");
            translations[currentLanguage].aboutList.forEach((item, index) => {
                aboutListItems[index].innerHTML = item;
            });

            document.querySelector("#current-status").innerHTML = translations[currentLanguage].currentStatus;
            document.querySelector("h2:nth-of-type(2)").textContent = translations[currentLanguage].educationTitle;

            const educationListItems = document.querySelectorAll("#education li");
            translations[currentLanguage].education.forEach((item, index) => {
                educationListItems[index].innerHTML = item;
            });

            document.querySelector("h2:nth-of-type(3)").textContent = translations[currentLanguage].portfolioTitle;
            document.querySelector("h4:nth-of-type(1)").textContent = translations[currentLanguage].mobileTitle;
            document.querySelector("h4:nth-of-type(2)").textContent = translations[currentLanguage].frontendTitle;
            document.querySelector("h4:nth-of-type(3)").textContent = translations[currentLanguage].backendTitle;
            document.querySelector("h4:nth-of-type(4)").textContent = translations[currentLanguage].desktopTitle;
        }

        function saveModeState() {
            var body = document.body;
            if (body.classList.contains("dark-mode")) {
                localStorage.setItem("darkMode", "enabled");
            } else {
                localStorage.setItem("darkMode", "disabled");
            }
        }

        window.onload = function() {
            var darkModeState = localStorage.getItem("darkMode");
            var body = document.body;
            if (darkModeState === "enabled") {
                body.classList.add("dark-mode");
                document.querySelector("#dark-mode-toggle button").textContent = translations[currentLanguage].lightMode;
            } else {
                body.classList.remove("dark-mode");
                document.querySelector("#dark-mode-toggle button").textContent = translations[currentLanguage].darkMode;
            }

            const savedLanguage = localStorage.getItem("language") || "pt-br";
            if (savedLanguage) {
                currentLanguage = savedLanguage;
                changeLanguage();
            }
        };

        window.onbeforeunload = function() {
            saveModeState();
            localStorage.setItem("language", currentLanguage);
        };

        let currentLanguage = "pt-br";
    </script>
