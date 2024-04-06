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

## Competências 
<details>
  <summary><Desenvolvimento de Sistemas - <strong>SENAI</strong></summary>
  
  <h4>Fundamentos de Programação Orientada a Objeto</h4>
  <ul>
    <li>Linguagem de programação <strong>Java</strong></li>
    <li>Lógica de programação orientada a objeto</li>
    <li>Programação orientada a objetos</li>
  </ul>

  <h4>Sistemas Operacionais</h4>
  <ul>
    <li>Arquitetura dos sistemas operacionais</li>
    <li>Sistema operacional código fechado</li>
    <li>Sistemas operacional código aberto</li>
    <li>Editor de texto</li>
    <li>Manipulação de arquivos</li>
    <li>Planilha eletrônica</li>
  </ul>

  <h4>Hardware e Redes de Computadores</h4>
  <ul>
    <li>Fundamentos de Hardware</li>
    <li>Fundamentos de Redes de Computadores</li>
  </ul>

  <h4>Linguagens de Marcação e Estilização</h4>
  <ul>
    <li>HTML 5</li>
    <li>CSS 3</li>
    <li>Materialize</li>
    <li>Acessibilidade</li>
    <li>Design responsivo</li>
    <li>User experience (UX) design</li>
  </ul>

  <h4>Programação Web Front-end</h4>
  <ul>
    <li>Javascript</li>
    <li>React</li>
    <li>Web apps</li>
  </ul>

  <h4>Banco de Dados</h4>
  <ul>
    <li>Sistema Gerenciador de Banco de Dados (SGBD)</li>
    <li>Modelo relacional (MySQL)</li>
    <li>Modelo não-relacional (Firebase)</li>
  </ul>

  <h4>Programação Web Back-end</h4>
  <ul>
    <li>Linguagem de programação <strong>C#</strong></li>
    <li>Padrão de desenvolvimento MVC</li>
    <li>.NET</li>
    <li>Persistência de dados</li>
    <li>Web Services</li>
  </ul>

  <h4>Interfaces para Dispositivos Móveis</h4>
  <ul>
    <li>Criação de Interfaces</li>
    <li>Recursos de Hardware</li>
  </ul>

  <h4>Programação Para Dispositivos</h4>
  <ul>
    <li>APIs</li>
    <li>Persistência de dados em dispositivos móveis</li>
    <li>Consumo de RESTful web services</li>
  </ul>

  <h4>Projetos</h4>
  <ul>
    <li>Qualidade de software</li>
    <li>Metodologias de desenvolvimento</li>
    <li>Metodologia de gerenciamento de projeto</li>
    <li>Apresentação do projeto</li>
  </ul>

  <h4>Requisitos e Modelagem de Software</h4>
  <ul>
    <li>Requisitos</li>
    <li>Levantamento de Requisitos</li>
    <li>Gerenciamento de Requisitos</li>
    <li>UML (Unified Modeling Language)</li>
    <li>Documentação de Requisitos</li>
  </ul>

  <h4>Testes de Software</h4>
  <ul>
    <li>Testes</li>
    <li>Planejamento de testes</li>
    <li>Execução de testes</li>
  </ul>

  <h5>Outros</h5>
  <ul>
    <li>Ambiente de desenvolvimento desktop</li>
    <li>Ambiente de desenvolvimento web</li>
    <li>Publicação de web sites</li>
    <li>Publicação do aplicativo</li>
    <li>Controle de versões</li>
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
