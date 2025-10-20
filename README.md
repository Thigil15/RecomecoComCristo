RecomecoComCristo - Jornada da Graça

Este repositório contém o código-fonte de uma Single Page Application (SPA) interativa, projetada para apresentar a mensagem cristã sobre graça e recomeço de uma forma moderna, envolvente e otimizada para dispositivos móveis.

Visão Geral do Projeto

O projeto "Jornada da Graça" nasceu da necessidade de transformar um panfleto evangelístico tradicional em uma experiência digital imersiva. O objetivo é capturar a atenção do usuário, que muitas vezes acessa a página através de um QR Code, e guiá-lo por uma jornada de reflexão pessoal.

A aplicação foi construída como uma narrativa visual, onde cada seção se baseia na anterior, utilizando técnicas de UI/UX e animações para manter o usuário engajado e focado na mensagem.

Features Principais

A aplicação é rica em interações e estilizações construídas com CSS e JavaScript puro para garantir leveza e performance.

Jornada Guiada: A estrutura da página não é apenas informativa, mas segue uma progressão narrativa: Questionamento -> Dilema -> Revelação -> Benefícios -> Ação.

Animações de Entrada: Elementos surgem na tela de forma suave conforme o usuário rola a página (IntersectionObserver), direcionando o foco e criando uma experiência dinâmica.

Título Animado: O título principal é revelado palavra por palavra para um impacto visual imediato.

Efeito Tilt 3D (Desktop): Na seção "O Peso do Passado", os cartões possuem um efeito de inclinação 3D que responde ao movimento do mouse, criando uma sensação de profundidade.

Interação Simbólica: O usuário "descarta" os pesos do passado ao clicar nos cartões, que se esmaecem, reforçando a mensagem de libertação.

Galeria de Dons Interativa: A antiga seção de "acordeão" foi substituída por uma galeria de cartões interativos que se expandem de forma elegante ao toque, revelando os benefícios da graça.

Animação de "Máquina de Escrever": A oração final é "digitada" na tela após um clique de confirmação do usuário, criando um momento de decisão e foco.

Navegação de Progresso: Um menu lateral discreto acompanha o progresso do usuário pela jornada, indicando em qual seção ele se encontra.

Design Responsivo (Mobile First): Toda a experiência foi desenhada primariamente para celulares, garantindo legibilidade e usabilidade perfeitas em telas pequenas.

Fundo Animado: Um sutil gradiente animado no background cria uma atmosfera serena e visualmente agradável.

Tecnologias Utilizadas

Este projeto foi construído com foco em performance e simplicidade, utilizando tecnologias web nativas.

HTML5: Para a estrutura semântica do conteúdo.

CSS3:

Tailwind CSS: Framework utilitário para agilidade na estilização e responsividade.

CSS Customizado: Animações (@keyframes), transições e efeitos visuais avançados.

JavaScript (ES6+):

Vanilla JS: Todo o dinamismo e interatividade são controlados com JavaScript puro, sem a necessidade de frameworks pesados, garantindo um carregamento rápido.

Intersection Observer API: Para gerenciar as animações que ocorrem durante o scroll da página.

Como Utilizar

Por ser uma aplicação self-contained, basta abrir o arquivo Index.html em qualquer navegador moderno. Não há dependências externas para instalar ou processos de build.

Este README serve como um documento técnico e conceitual do projeto, refletindo a atenção aos detalhes e a busca por uma experiência de usuário de alta qualidade.
