# Currículo Interativo | Interactive Resume

Este é um currículo web interativo e de página única, projetado para apresentar de forma moderna e dinâmica a trajetória profissional, competências e projetos de Francisco Nilton Freire Filho.

This is a single-page, interactive web resume designed to present the professional journey, skills, and projects of Francisco Nilton Freire Filho in a modern and dynamic way.

## 🧐 Como Foi Feito (How It Was Made)

O projeto foi construído do zero, utilizando tecnologias web modernas para criar uma experiência de usuário rica e fluida, similar a uma Single-Page Application (SPA), mas sem a necessidade de um framework JavaScript complexo.

-   **Estrutura e Conteúdo**: O HTML5 foi usado para estruturar todo o conteúdo de forma semântica. Os dados da carreira, formação e traduções são armazenados em objetos JavaScript, facilitando a manutenção e a atualização.
-   **Estilo e Design**: O design foi implementado com **Tailwind CSS**, permitindo a criação de uma interface moderna e totalmente responsiva (mobile-first) de forma ágil. Estilos customizados foram adicionados para funcionalidades específicas, como o modo escuro e animações.
-   **Interatividade**: A interatividade foi desenvolvida com **JavaScript (ES6+)** puro. O código manipula o DOM para funcionalidades como a troca de idiomas, o tema claro/escuro, a expansão da linha do tempo e a exibição de modais, tudo sem recarregar a página.
-   **Visualização de Dados**: Para exibir as competências de forma visual, foi utilizada a biblioteca **Chart.js**, que gera um gráfico de barras interativo.
-   **Recursos Externos**: O projeto se conecta ao **Firebase** (Firestore) para implementar um contador de visitantes em tempo real, adicionando um toque dinâmico e demonstrando a integração com serviços de back-end.

---

The project was built from scratch using modern web technologies to create a rich and fluid user experience, similar to a Single-Page Application (SPA), but without the need for a complex JavaScript framework.

-   **Structure and Content**: HTML5 was used to structure all content semantically. Career data, education, and translations are stored in JavaScript objects, making maintenance and updates easy.
-   **Style and Design**: The design was implemented with **Tailwind CSS**, allowing for the agile creation of a modern and fully responsive (mobile-first) interface. Custom styles were added for specific features like dark mode and animations.
-   **Interactivity**: Interactivity was developed with pure **JavaScript (ES6+)**. The code manipulates the DOM for features like language switching, light/dark theme, timeline expansion, and modal displays, all without reloading the page.
-   **Data Visualization**: To display skills visually, the **Chart.js** library was used to generate an interactive bar chart.
-   **External Resources**: The project connects to **Firebase** (Firestore) to implement a real-time visitor counter, adding a dynamic touch and demonstrating integration with back-end services.

## ✨ Funcionalidades Implementadas (Implemented Features)

-   **Tema Claro/Escuro**: Permite ao usuário alternar entre um tema claro e um escuro para melhor conforto visual. A preferência é salva no `localStorage` do navegador.
-   **Suporte Multilíngue (PT/EN)**: Todo o conteúdo textual pode ser alternado dinamicamente entre Português e Inglês.
-   **Linha do Tempo Interativa**: A experiência profissional é exibida em uma linha do tempo onde cada item pode ser expandido para revelar mais detalhes.
-   **Gráfico de Competências**: Um gráfico de barras gerado com Chart.js mostra as habilidades do profissional de forma visual e agrupada por categoria.
-   **Contador de Visitantes**: Utiliza o Firebase Firestore para exibir o número total de visitantes que acessaram a página.
-   **Versão para Impressão**: Uma folha de estilo otimizada para impressão (`@media print`) formata o conteúdo em um layout de currículo tradicional, removendo elementos interativos.
-   **Totalmente Responsivo**: O layout se adapta perfeitamente a qualquer tamanho de tela, de dispositivos móveis a desktops.

---

-   **Light/Dark Theme**: Allows the user to switch between a light and a dark theme for better visual comfort. The preference is saved in the browser's `localStorage`.
-   **Multilingual Support (PT/EN)**: All textual content can be dynamically switched between Portuguese and English.
-   **Interactive Timeline**: Professional experience is displayed in a timeline where each item can be expanded to reveal more details.
-   **Skills Chart**: A bar chart generated with Chart.js visually displays the professional's skills, grouped by category.
-   **Visitor Counter**: Uses Firebase Firestore to display the total number of visitors who have accessed the page.
-   **Print-Friendly Version**: A print-optimized stylesheet (`@media print`) formats the content into a traditional resume layout, removing interactive elements.
-   **Fully Responsive**: The layout adapts perfectly to any screen size, from mobile devices to desktops.

## 🚀 Tecnologias Utilizadas (Technologies Used)

-   **HTML5**: Linguagem de marcação para a estrutura semântica da página.
-   **CSS3**: Utilizado para estilizações customizadas e para a versão de impressão.
-   **Tailwind CSS**: Framework CSS utility-first para a criação rápida de interfaces modernas e responsivas.
-   **JavaScript (ES6+)**: Linguagem de programação que adiciona toda a interatividade e lógica à página.
-   **Chart.js**: Biblioteca para criar gráficos e visualizações de dados em JavaScript.
-   **Firebase (Auth & Firestore)**: Plataforma do Google usada para o contador de visitantes em tempo real, com autenticação anônima para segurança.
-   **Google Fonts**: Para a tipografia (família de fontes 'Inter').
-   **Git & GitHub**: Para versionamento de código e hospedagem do projeto no GitHub Pages.

---

-   **HTML5**: Markup language for the semantic structure of the page.
-   **CSS3**: Used for custom styling and the print version.
-   **Tailwind CSS**: A utility-first CSS framework for rapidly building modern and responsive interfaces.
-   **JavaScript (ES6+)**: The programming language that adds all interactivity and logic to the page.
-   **Chart.js**: A library for creating charts and data visualizations in JavaScript.
-   **Firebase (Auth & Firestore)**: Google's platform used for the real-time visitor counter, with anonymous authentication for security.
-   **Google Fonts**: For typography (the 'Inter' font family).
-   **Git & GitHub**: For code versioning and hosting the project on GitHub Pages.

## ▶️ Como Rodar o Projeto (How to Run the Project)

Este projeto é um site estático, mas para que a funcionalidade do Firebase (contador de visitantes) funcione corretamente, ele precisa ser servido por um servidor web, e não aberto diretamente do sistema de arquivos (`file://`).

This project is a static website, but for the Firebase functionality (visitor counter) to work correctly, it needs to be served by a web server, not opened directly from the file system (`file://`).

**Opção 1: Acessar a versão online (Online Version)**

A maneira mais fácil é acessar a versão já publicada: **[https://devinfreire.github.io/](https://devinfreire.github.io/)**

The easiest way is to access the already published version: **[https://devinfreire.github.io/](https://devinfreire.github.io/)**

**Opção 2: Rodar localmente com um servidor (Run Locally with a Server)**

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/DEVinFreire/DEVinFreire.github.io.git
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd DEVinFreire.github.io
    ```
3.  **Inicie um servidor local.** Se você tiver o Node.js instalado, pode usar o `npx`:
    ```bash
    npx serve
    ```
    Ou, se tiver Python 3 instalado:
    ```bash
    python -m http.server
    ```
4.  Abra o navegador e acesse `http://localhost:3000` (para `serve`) ou `http://localhost:8000` (para Python).