# Felipe Macedo dos Santos
<div id="dark-mode-toggle">
  <button onclick="toggleDarkMode()">Toggle Dark Mode</button>
</div>

<script>
function toggleDarkMode() {
    var body = document.body;
    body.classList.toggle("dark-mode");
}

// Cria uma função para salvar o estado do modo no localStorage
function saveModeState() {
    var body = document.body;
    if (body.classList.contains("dark-mode")) {
        localStorage.setItem("darkMode", "enabled");
    } else {
        localStorage.setItem("darkMode", "disabled");
    }
}

// Carrega o estado do modo salvo no localStorage ao carregar a página
window.onload = function() {
    var darkModeState = localStorage.getItem("darkMode");
    var body = document.body;
    if (darkModeState === "enabled") {
        body.classList.add("dark-mode");
    } else {
        body.classList.remove("dark-mode");
    }
};

// Adiciona um evento para salvar o estado do modo ao fechar a página
window.onbeforeunload = saveModeState;
</script>

<style>
/* Estilos para os modos claro e escuro */
body {
    transition: background-color 0.4s ease;
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
