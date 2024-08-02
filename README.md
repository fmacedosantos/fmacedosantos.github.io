
# Felipe Macedo dos Santos
Altere entre modo Claro e Escuro: 
<div id="dark-mode-toggle">
  <button onclick="toggleDarkMode()">Claro / Escuro</button>
</div>
>_Conheça a minha história e o meu portfólio._

## Sobre mim
Meu interesse pela área da programação começou há cerca de 2 anos e meio. A minha trajetória de estudos começou com cursos livres na internet, onde realmente despertou o meu entusiamo pela área. Atualmente, estou finalizando meu **técnico em Desenvolvimento de Sistemas** (3 / 4). Além disso, estou cursando **Ciência da Computação** (1 / 8).
No curso de nível técnico, desde o início, fomos colocados em grupos de 4 integrantes, seguindo a metodologia ágil _Scrum_. Essa dinâmica ofereceu experiências de trabalho de desenvolvimento de sistemas em times diversificados e com diferentes habilidades em diferentes áreas. 
>Essa vivência fortaleceus habilidades como **Trabalho em Equipe**, **Liderança**, **Gestão de Tempo**, **Organização**, **Distribuição de Tarefas**, **Comunicação**, entre outras.

## Portfólio 
<details>
    <summary><strong>Projetos</strong></summary>

    <h4><strong>Mobile</strong></h4>
    <ul>
        <li><a href="https://github.com/fmacedosantos/tickUpMobile">TickUp (Android Studio)</a></li>
        <li><a href="https://github.com/fmacedosantos/mobile-orgs-cesta">Cesta Virtual (React Native)</a></li>
    </ul>

    <h4><strong>Back-end</strong></h4>
    <ul>
      <li><a href="https://github.com/fmacedosantos/tickUpAPI">TickUp: API (ASP.NET)</a></li>
    </ul>

    <h4><strong>Fron-end</strong></h4>
    <ul>
        <li><a href="https://github.com/GustavoGuimaraes01/TickUp">TickUp</a></li>
        <li><a href="https://github.com/fmacedosantos/alura_space">Alura Space</a></li>
    </ul>
    
    <h4><strong>Desktop</strong></h4>
    <ul>
        <li><a href="https://github.com/fmacedosantos/AdvocateLinkDesktop">AdvocateLink (Java)</a></li>
        <li><a href="https://github.com/fmacedosantos/AquaZen">AquaZen (Java)</a></li>
        <li><a href="https://github.com/fmacedosantos/sistema_bancario">Sistema bancário (Python)</a></li>
        <li><a href="https://github.com/fmacedosantos/vetorAleatorioC">Vetor aleatório (C)</a></li>
    </ul>
    
</details>



<script>
function toggleDarkMode() {
    var body = document.body;
    body.classList.toggle("dark-mode");
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
/* estilos para os modos claro e escuro */
body {
    transition: background-color 0.4s ease;
}

div {
  margin-bottom: 5px;
}

.light-mode {
    background-color: #ffffff;
    color: #333333;
}

.dark-mode {
    background-color: #333333;
    color: #ffffff;
}
</style>
