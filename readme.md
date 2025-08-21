# **Currículo Interativo \- Francisco Nilton Freire Filho**

[Read this document in English](https://www.google.com/search?q=%23-interactive-resume---francisco-nilton-freire-filho)

Este é um projeto de currículo interativo de página única, projetado para apresentar de forma dinâmica e moderna as informações profissionais de Francisco Nilton Freire Filho. A página é totalmente responsiva, multilíngue e inclui várias funcionalidades interativas para melhorar a experiência do usuário.

## **🚀 Visão Geral do Projeto**

O objetivo deste projeto é ir além de um currículo tradicional em PDF, oferecendo uma experiência web que não só detalha a jornada profissional, mas também demonstra habilidades práticas de desenvolvimento front-end. Ele foi construído como um arquivo HTML único para simplicidade e portabilidade.

## **✨ Funcionalidades Principais**

* **Design Responsivo:** Totalmente adaptável para visualização em desktops, tablets e dispositivos móveis.  
* **Modo Claro e Escuro (Dark/Light Mode):** Permite que o usuário alterne entre temas para melhor conforto visual. A preferência do sistema é detectada e aplicada no primeiro acesso.  
* **Suporte Multilíngue (i18n):** O conteúdo pode ser visualizado em Português (PT) e Inglês (EN), com a troca de idioma ocorrendo instantaneamente.  
* **Linha do Tempo da Carreira Interativa:** As experiências profissionais são apresentadas em uma linha do tempo onde cada item pode ser expandido para exibir mais detalhes.  
* **Gráfico de Competências:** Um gráfico de barras gerado com Chart.js que visualiza os níveis de proficiência em diferentes áreas de habilidade.  
* **Contador de Visitantes:** Utiliza o Firebase (Firestore) para registrar e exibir o número de visitantes únicos da página.  
* **Versão para Impressão:** Uma folha de estilo otimizada para impressão é aplicada ao acionar a função de imprimir, gerando um currículo limpo e bem formatado.  
* **Animações e Transições:** Efeitos sutis em CSS são usados para criar uma navegação mais fluida e agradável.

## **🛠️ Tecnologias Utilizadas**

O projeto foi construído utilizando tecnologias de front-end modernas, com dependências carregadas via CDN para simplificar a configuração.

* **HTML5:** Para a estrutura semântica do conteúdo.  
* **CSS3:** Para estilizações personalizadas, animações e a folha de estilo de impressão.  
* **Tailwind CSS:** Um framework CSS utility-first para a construção rápida de interfaces customizadas. É carregado via CDN.  
* **JavaScript (ES6+):** Responsável por toda a interatividade da página, incluindo:  
  * Manipulação do DOM.  
  * Lógica para o modo claro/escuro.  
  * Funcionalidade de tradução (i18n).  
  * Interação com a linha do tempo e outros componentes.  
* **Chart.js:** Uma biblioteca para criar gráficos dinâmicos e visualmente atraentes. Usada na seção de competências.  
* **Firebase (Firestore):** Utilizado como back-end para a funcionalidade de contador de visitantes. A autenticação é anônima para simplificar o processo.

## **⚙️ Como Rodar o Projeto**

Como este projeto é um único arquivo index.html que carrega todas as suas dependências (CSS e JS) de CDNs, não há necessidade de um processo de build ou de um servidor local.

Para executá-lo, basta seguir estes passos:

1. Faça o download do arquivo index.html.  
2. Abra o arquivo em qualquer navegador de internet moderno (como Google Chrome, Firefox, Safari ou Edge).

E pronto\! A página será carregada e todas as funcionalidades estarão disponíveis.

## **📂 Estrutura do Arquivo**

Todo o código está contido no arquivo index.html, organizado da seguinte forma:

1. **\<head\>:**  
   * Meta tags para configuração da página.  
   * Links para as fontes do Google Fonts.  
   * Scripts de CDN para Tailwind CSS e Chart.js.  
   * Tag \<style\> com todo o CSS personalizado, incluindo estilos para o modo escuro e para impressão.  
2. **\<body\>:**  
   * Estrutura HTML dividida em seções semânticas (\<header\>, \<aside\>, \<main\>).  
   * Uso de classes do Tailwind CSS para estilização.  
   * Atributos data-key para facilitar a internacionalização do conteúdo via JavaScript.  
3. **\<script type="module"\>:**  
   * Todo o código JavaScript do projeto está localizado no final do \<body\>.  
   * Importações do Firebase SDK (módulos App, Firestore, Auth).  
   * Configuração e inicialização do Firebase.  
   * Lógica para o contador de visitantes.  
   * Objeto i18n contendo os textos em português e inglês.  
   * Funções para renderizar conteúdo dinâmico (linha do tempo, gráfico, traduções).  
   * Listeners de eventos para os botões de tema, idioma, impressão e outros elementos interativos.

# **🇺🇸 Interactive Resume \- Francisco Nilton Freire Filho**

[Leia este documento em Português](https://www.google.com/search?q=%23-curr%C3%ADculo-interativo---francisco-nilton-freire-filho)

This is a single-page interactive resume project designed to dynamically and modernly present the professional information of Francisco Nilton Freire Filho. The page is fully responsive, multilingual, and includes various interactive features to enhance the user experience.

## **🚀 Project Overview**

The goal of this project is to go beyond a traditional PDF resume by offering a web experience that not only details the professional journey but also demonstrates practical front-end development skills. It was built as a single HTML file for simplicity and portability.

## **✨ Key Features**

* **Responsive Design:** Fully adaptable for viewing on desktops, tablets, and mobile devices.  
* **Dark/Light Mode:** Allows the user to switch between themes for better visual comfort. The system preference is detected and applied on the first visit.  
* **Multilingual Support (i18n):** The content can be viewed in Portuguese (PT) and English (EN), with the language switch occurring instantly.  
* **Interactive Career Timeline:** Professional experiences are presented in a timeline where each item can be expanded to display more details.  
* **Skills Chart:** A bar chart generated with Chart.js that visualizes proficiency levels in different skill areas.  
* **Visitor Counter:** Uses Firebase (Firestore) to record and display the number of unique page visitors.  
* **Print Version:** A print-optimized stylesheet is applied when triggering the print function, generating a clean and well-formatted resume.  
* **Animations and Transitions:** Subtle CSS effects are used to create a smoother and more pleasant navigation experience.

## **🛠️ Technologies Used**

The project was built using modern front-end technologies, with dependencies loaded via CDN to simplify setup.

* **HTML5:** For the semantic structure of the content.  
* **CSS3:** For custom styling, animations, and the print stylesheet.  
* **Tailwind CSS:** A utility-first CSS framework for rapidly building custom interfaces. It is loaded via CDN.  
* **JavaScript (ES6+):** Responsible for all page interactivity, including:  
  * DOM manipulation.  
  * Logic for dark/light mode.  
  * Translation functionality (i18n).  
  * Interaction with the timeline and other components.  
* **Chart.js:** A library for creating dynamic and visually appealing charts. Used in the skills section.  
* **Firebase (Firestore):** Used as a back-end for the visitor counter functionality. Authentication is anonymous to simplify the process.

## **⚙️ How to Run the Project**

As this project is a single index.html file that loads all its dependencies (CSS and JS) from CDNs, there is no need for a build process or a local server.

To run it, simply follow these steps:

1. Download the index.html file.  
2. Open the file in any modern web browser (such as Google Chrome, Firefox, Safari, or Edge).

And that's it\! The page will load, and all features will be available.

## **📂 File Structure**

All the code is contained within the index.html file, organized as follows:

1. **\<head\>:**  
   * Meta tags for page configuration.  
   * Links to Google Fonts.  
   * CDN scripts for Tailwind CSS and Chart.js.  
   * A \<style\> tag with all custom CSS, including styles for dark mode and printing.  
2. **\<body\>:**  
   * HTML structure divided into semantic sections (\<header\>, \<aside\>, \<main\>).  
   * Use of Tailwind CSS classes for styling.  
   * data-key attributes to facilitate content internationalization via JavaScript.  
3. **\<script type="module"\>:**  
   * All of the project's JavaScript code is located at the end of the \<body\>.  
   * Imports from the Firebase SDK (App, Firestore, Auth modules).  
   * Firebase configuration and initialization.  
   * Logic for the visitor counter.  
   * An i18n object containing the texts in Portuguese and English.  
   * Functions to render dynamic content (timeline, chart, translations).  
   * Event listeners for the theme, language, print buttons, and other interactive elements.