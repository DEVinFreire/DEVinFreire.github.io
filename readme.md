# 📄 Currículo Interativo | Interactive Resume - Francisco Nilton Freire Filho

## 🇧🇷 Versão em Português

### 📖 Sobre o Projeto

Este projeto é um currículo interativo e dinâmico, criado para apresentar minhas competências, experiências e jornada profissional de uma forma moderna e visualmente atraente. A página é totalmente responsiva e foi desenvolvida com foco na usabilidade e na apresentação clara das informações. O projeto é hospedado diretamente no GitHub Pages.

### ✨ Funcionalidades Principais

-   **Linha do Tempo Interativa:** Navegue pela minha carreira com uma linha do tempo onde cada experiência pode ser expandida para ver mais detalhes.
-   **Contador de Visitantes:** Um contador em tempo real que utiliza o Firebase para registrar e exibir o número de visitantes da página.
-   **Gráfico de Competências:** Um gráfico de barras (Chart.js) que ilustra visualmente minhas principais áreas de habilidade.
-   **Suporte Multilíngue:** O conteúdo pode ser alternado entre Português (PT-BR) e Inglês (EN).
-   **Versão para Impressão:** Uma folha de estilos otimizada para impressão que formata o currículo em um layout A4 tradicional.
-   **Design Responsivo:** A interface se adapta perfeitamente a desktops, tablets e dispositivos móveis.
-   **Modal de Carta de Apresentação:** Uma carta de apresentação que pode ser visualizada em um modal.

### 🚀 Tecnologias Utilizadas

-   **Frontend:**
    -   HTML5
    -   Tailwind CSS (utilizado via CDN para estilização rápida e responsiva)
    -   JavaScript (Vanilla JS, ES6+) para interatividade e manipulação do DOM.
-   **Bibliotecas JavaScript:**
    -   **Chart.js:** Para a criação do gráfico de habilidades.
-   **Backend & Infraestrutura:**
    -   **Firebase Firestore:** Utilizado como banco de dados NoSQL para o contador de visitantes.
    -   **Firebase Authentication:** Para autenticação anônima de usuários para o contador.
    -   **GitHub Pages:** Para hospedagem e deploy contínuo do site.

### 🖥️ Como Visualizar

**Online (Recomendado):**

O projeto está no ar e pode ser acessado através do seguinte link:
[https://devinfreire.github.io/](https://devinfreire.github.io/)

**Localmente:**

1.  Clone o repositório:
    ```bash
    git clone https://github.com/DEVinFreire/DEVinFreire.github.io.git
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd DEVinFreire.github.io
    ```
3.  Abra o arquivo `index.html` em qualquer navegador moderno.

> **⚡ Nota sobre o Firebase:** Para que o contador de visitantes funcione localmente, é necessário ter as credenciais do Firebase configuradas no código.

### 👨‍💻 Como Foi Desenvolvido

O currículo foi construído do zero, utilizando uma abordagem de "página única" (Single Page Application). A estrutura é baseada em um único arquivo `index.html`, que contém todo o layout.

A estilização foi feita com **Tailwind CSS**, importado via CDN para agilizar o desenvolvimento e manter o projeto leve. As fontes utilizadas são do Google Fonts.

Toda a interatividade, como a troca de idiomas, a linha do tempo expansível e a lógica do modal, foi implementada com **JavaScript puro (Vanilla JS)**, manipulando o DOM diretamente. O conteúdo em múltiplos idiomas é armazenado em um objeto JavaScript dentro do script principal.

Para o contador de visitantes, foi integrada a plataforma **Firebase**. A autenticação anônima permite identificar sessões de usuário sem exigir login, e o **Firestore** (um banco de dados NoSQL) armazena e incrementa o número de visitas. As chamadas para o Firebase são feitas de forma assíncrona para não bloquear o carregamento da página.

O gráfico de habilidades é renderizado pela biblioteca **Chart.js**, que foi escolhida por sua simplicidade e poder de visualização.

---

## 🇬🇧 English Version

### 📖 About The Project

This project is an interactive and dynamic resume, created to showcase my skills, experiences, and professional journey in a modern and visually appealing way. The page is fully responsive and was developed with a focus on usability and clear information presentation. The project is hosted directly on GitHub Pages.

### ✨ Key Features

-   **Interactive Timeline:** Navigate through my career with a timeline where each experience can be expanded for more details.
-   **Visitor Counter:** A real-time counter that uses Firebase to record and display the number of page visitors.
-   **Skills Chart:** A bar chart (Chart.js) that visually illustrates my main skill areas.
-   **Multi-language Support:** The content can be switched between Portuguese (PT-BR) and English (EN).
-   **Print-Friendly Version:** A print-optimized stylesheet that formats the resume into a traditional A4 layout.
-   **Responsive Design:** The interface adapts seamlessly to desktops, tablets, and mobile devices.
-   **Cover Letter Modal:** A cover letter that can be viewed in a modal window.

### 🚀 Technologies Used

-   **Frontend:**
    -   HTML5
    -   Tailwind CSS (used via CDN for rapid and responsive styling)
    -   JavaScript (Vanilla JS, ES6+) for interactivity and DOM manipulation.
-   **JavaScript Libraries:**
    -   **Chart.js:** For creating the skills chart.
-   **Backend & Infrastructure:**
    -   **Firebase Firestore:** Used as a NoSQL database for the visitor counter.
    -   **Firebase Authentication:** For anonymous user authentication for the counter.
    -   **GitHub Pages:** For hosting and continuous deployment of the site.

### 🖥️ How to View

**Online (Recommended):**

The project is live and can be accessed via the following link:
[https://devinfreire.github.io/](https://devinfreire.github.io/)

**Locally:**

1.  Clone the repository:
    ```bash
    git clone https://github.com/DEVinFreire/DEVinFreire.github.io.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd DEVinFreire.github.io
    ```
3.  Open the `index.html` file in any modern browser.

> **⚡ Note on Firebase:** For the visitor counter to work locally, you need to have Firebase credentials configured in the code.

### 👨‍💻 How It Was Developed

The resume was built from scratch using a Single Page Application approach. The structure is based on a single `index.html` file, which contains the entire layout.

Styling was done with **Tailwind CSS**, imported via CDN to speed up development and keep the project lightweight. The fonts used are from Google Fonts.

All interactivity, such as language switching, the expandable timeline, and the modal logic, was implemented with **Vanilla JavaScript**, manipulating the DOM directly. The multilingual content is stored in a JavaScript object within the main script.

For the visitor counter, the **Firebase** platform was integrated. Anonymous authentication allows identifying user sessions without requiring a login, and **Firestore** (a NoSQL database) stores and increments the visit count. Calls to Firebase are made asynchronously to avoid blocking the page load.

The skills chart is rendered by the **Chart.js** library, which was chosen for its simplicity and powerful visualization capabilities.