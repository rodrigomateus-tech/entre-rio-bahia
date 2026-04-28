![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# Entre o Rio e a Bahia 💙 | Interactive Landing Page

Uma landing page interativa e responsiva construída com foco em animações fluidas, manipulação de DOM e storytelling visual. 

Originalmente desenvolvido como um presente pessoal, o projeto foi refatorado e escalado para servir como um **template customizável** para desenvolvimento front-end focado em micro-interações.

## O Desafio Técnico

A tecnologia muitas vezes foca em ferramentas de gestão, mas o objetivo deste projeto foi utilizar fundamentos sólidos de Front-end para criar uma "carta digital" moderna e engajadora. 

O desafio envolveu orquestrar múltiplos eventos de tempo (contadores regressivos), gerenciar a visibilidade de elementos com base no scroll do usuário (Intersection Observer) e garantir uma experiência *mobile-first* impecável através do TailwindCSS, tudo sem depender de frameworks pesados de JavaScript (Zero Dependencies).

## Principais Funcionalidades

* **Controle de Tempo Real:** Contador regressivo dinâmico construído em Vanilla JS, com cálculos precisos de data e animações de pulo (*jump animations*) acionadas via manipulação de classes CSS a cada segundo percorrido.
* **Scroll Interativo (Lazy Animation):** Implementação da API nativa `IntersectionObserver` para revelar seções da página gradualmente (`fade-in-section`), otimizando o rendering e a retenção visual.
* **Carrossel de Imagens Acessível:** Slider customizado desenvolvido do zero, com controle de estado nativo, transições fluidas e marcações ARIA (`aria-label`) para leitores de tela.
* **Animações CSS Avançadas:** Uso de `@keyframes` para criar fundos com gradientes dinâmicos, cursores de digitação realistas e elementos pulsantes.
* **Sistema de Easter Egg:** Lógica de monitoramento de cliques consecutivos (`addEventListener`) aplicada ao DOM que revela componentes ocultos de forma assíncrona com `setTimeout`.

## Tecnologias Utilizadas

* **HTML5** (Semântico e estruturado)
* **CSS3 & TailwindCSS** (Estilização utilitária e componentização visual responsiva)
* **JavaScript (ES6+)** (Vanilla JS para toda a reatividade, separação de responsabilidades em `main.js`)

## Como Executar e Customizar

Este projeto foi modularizado para fácil manutenção. Para rodar localmente:

1. Faça o clone do repositório:
   ```bash
   git clone [https://github.com/rodrigomateus-tech/entre-rio-bahia.git](https://github.com/rodrigomateus-tech/entre-rio-bahia.git)
   
2. Abra o arquivo index.html no seu navegador ou utilize a extensão Live Server no VSCode.

3. Customização:

Lógica e Datas: Abra assets/js/main.js e altere a constante targetReunionDate.

Estilos: As animações customizadas encontram-se em assets/css/style.css.

Conteúdo: Procure pelos comentários `` no index.html para substituir imagens e links.

## Autor

Desenvolvido por Rodrigo Mateus Silva  
[linkedin.com/in/rodrigo-mateus-ti](https://linkedin.com/in/rodrigo-mateus-ti)
