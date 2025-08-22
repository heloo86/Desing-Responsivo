# Landing page baseada em Protótipo Figma para HTML/CSS

Este projeto é a implementação prática de uma landing page responsiva, desenvolvida como parte da atividade de Prática de HTML e CSS. O objetivo principal foi converter um design de alta fidelidade, fornecido através de um protótipo no Figma, em uma página web totalmente responsiva utilizando as melhores práticas de desenvolvimento front-end.

## ✒️ Autor

*   **Desenvolvido por:** Heloisa Almeida Ferreira
*   **GitHub:** heloo86

---

## 📋 Índice

*   [Descrição do Projeto](#-descrição-do-projeto)
*   [Conhecimentos aplicados ](#-conhecimentos-aplicados)
*   [Tecnologias Utilizadas](#-tecnologias-utilizadas)
*   [Como Executar o Projeto](#-como-executar-o-projeto)

---

## 📝 Descrição do Projeto

O desafio consistiu em recriar uma landing page com fidelidade total a dois layouts de referência: mobile (375px) e desktop (1440px). O desenvolvimento seguiu a abordagem **Mobile First**, garantindo uma experiência de usuário otimizada em telas menores como ponto de partida, e adaptando a interface para telas maiores através de *media queries*.

O foco do projeto foi além da simples replicação visual, abranger a aplicação de conceitos fundamentais como semântica HTML, organização e reutilização de estilos CSS


---

## ✅ Conhecimentos aplicados 

Este projeto foi desenvolvido com o objetivo de desenvolver conhecimeneto a cerca da utilização de ferramentas HTML e CSS onde foram aplicadas flex-basis, @média, variaveis css utilização de medidas adapatativas como vh vw entre outros que incluem: 

### Layout e Responsividade

*   **Fidelidade ao Layout Mobile e Desktop:** O código foi estruturado para reproduzir com máxima precisão os protótipos fornecidos, respeitando cores, fontes, espaçamentos e posicionamento dos elementos em ambas as versões.
*   **Abordagem Mobile First:** O `style.css` foi escrito primeiramente para a versão de 375px. As adaptações para o layout de 1440px foram encapsuladas em um bloco `@media screen and (min-width: 848px)`, garantindo um carregamento otimizado para dispositivos móveis.

### Estrutura e Boas Práticas de Código

*   **Tags Semânticas:** A estrutura do `index.html` foi construída utilizando tags semânticas do HTML5 para dar significado e acessibilidade ao conteúdo, incluindo `<header>`, `<footer>`, `<section>`, `<main>`, e `<nav>`.
*   **Organização e Separação de Conteúdo:** Foi mantida uma separação clara de responsabilidades:
    *   `index.html`: Responsável exclusivamente pela estrutura e conteúdo.
    *   `style.css`: Responsável exclusivamente pela apresentação e estilo.
    *   O código em ambos os arquivos está devidamente indentado e organizado em seções lógicas comentadas, facilitando a leitura e manutenção.
*   **Uso de Classes e IDs Descritivos:** As classes CSS seguem um padrão de nomenclatura coerente e descritivo (ex: `.profile-card`, `.footer-actions`, `.contact-in`), tornando o código autoexplicativo.
*   **Otimização e Reutilização de Estilos CSS:** Foram criadas classes utilitárias reutilizáveis, como `.btn` e `.title`, para componentes que se repetem ao longo da página. Isso evita a duplicação de código e promove a consistência visual.
*   **Utilização de Variáveis CSS:** As cores primárias, secundárias e as fontes do projeto foram centralizadas como variáveis CSS no seletor `:root`. Isso permite uma manutenção fácil e rápida do tema visual do site.

    ```css
    :root {
        --primary-color: #FFA500; /* Exemplo */
        --secondary-color: #FAFAFA; /* Exemplo */
        --text-font: 'Sua Fonte', sans-serif; /* Exemplo */
    }
    ```
---

## 🛠️ Tecnologias Utilizadas

*   **HTML5:** Para a estruturação semântica do conteúdo.
*   **CSS3:** Para a estilização, responsividade e uso de tecnologias modernas como Flexbox, CSS Grid e Variáveis CSS.
*   **Figma:** Para protótipo de referência.
      *  link para o protótipo: https://www.figma.com/design/8V5FWEZnOTonjQcfTCdNJ8/Desing-Responsivo?node-id=0-1&t=YNsTwauT9bnWOJeu-1

---

## 🚀 Como Executar o Projeto

Este projeto consiste apenas em arquivos estáticos (`.html`, `.css`, imagens) e não requer nenhuma dependência ou servidor para ser executado.

1.  **Baixe e Descompacte:** Faça o download do arquivo `.zip` e descompacte-o em uma pasta de sua preferência.
2.  **Abra o Arquivo HTML:** Navegue até a pasta descompactada e abra o arquivo `index.html` em qualquer navegador de internet moderno (Google Chrome, Firefox, Microsoft Edge, etc.).

O site será renderizado localmente no seu navegador.
