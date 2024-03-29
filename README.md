# Felipe Macedo dos Santos
Altere para o modo <div id="dark-mode-toggle">
  <button onclick="toggleDarkMode()">Dark</button>
</div>
>_Conheça a minha história e o meu portfólio._

## Sobre mim
Meu interesse pela área da programação começou há cerca de 2 anos e meio. A minha trajetória de estudos começou com cursos livres na internet, onde realmente despertou o meu entusiamo pela área. Atualmente, estou finalizando meu **técnico em Desenvolvimento de Sistemas** (3 / 4). Além disso, estou cursando **Ciência da Computação** (1 / 8).
No curso de nível técnico, desde o início, fomos colocados em grupos de 4 integrantes, seguindo a metodologia ágil _Scrum_. Essa dinâmica ofereceu experiências de trabalho de desenvolvimento de sistemas em times diversificados e com diferentes habilidades em diferentes áreas. 
>Essa vivência fortaleceus habilidades como **Trabalho em Equipe**, **Liderança**, **Gestão de Tempo**, **Organização**, **Distribuição de Tarefas**, **Comunicação**, entre outras.
## Competências 
### Desenvolvimento de Sistemas - **SENAI**
#### Fundamentos de Programação Orientada a Objeto
* Linguagem de programação **Java**
* Lógica de programação orientada a objeto
* Programação orientada a objetos
#### Sistemas Operacionais
* Arquitetura dos sistemas operacionais
* Sistema operacional código fechado
* Sistemas operacional código aberto
* Editor de texto
* Manipulação de arquivos
* Planilha eletrônica.
#### Hardware e Redes de Computadores
* Fundamentos de Hardware
* Fundamentos de Redes de Computadores
#### Linguagens de Marcação e Estilização
* HTML 5
* CSS 3
* Materialize
* Acessibilidade
* Design responsivo
* User experience (UX) design
#### Programação Web Front-end
* Javascript
* React
* Web apps
#### Banco de Dados
* Sistema Gerenciador de Banco de Dados (SGBD)
* Modelo relacional (MySQL)
* Modelo não-relacional (Firebase)
#### Programação Web Back-end
* Linguagem de programação **C#**
* Padrão de desenvolvimento MVC
* .NET
* Persistência de dados
* Web Services
#### Interfaces para Dispositivos Móveis
* Criação de Interfaces
* Recursos de Hardware
#### Programação Para Dispositivos 
* APIs
* Persistência de dados em dispositivos móveis
* Consumo de RESTfull web servisse
#### Projetos
* Qualidade de software
* Metodologias de desenvolvimento
* Metodologia de gerenciamento de projeto
* Apresentação do projeto
#### Requisitos e Modelagem de Software
* Requisitos
* Levantamento de Requisitos
* Gerenciamento de Requisitos
* UML (Unified Modeling Language)
* Documentação de Requisitos
#### Testes de Software
* Testes
* Planejamento de testes
* Execução de testes
##### Outros
* Ambiente de desenvolvimento desktop
* Ambiente de desenvolvimento web
* Publicação de web sites
* Publicação do aplicativo
* Controle de versões.

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
