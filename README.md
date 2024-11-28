# Projeto Prático de HTML E CSS

## Cronstruindo um site com focas

Neste projeto prático, busquei consolidar alguns dos conhecimentos adquiridos de HTML5 E  CSS3, vistos
ao longo dos meus estudos, revisando várias propriedades e também conhecendo novas
propriedades. O objetivo é construir um site realista, com requisitos reais, utilizando muitas
propriedades CSS.

## ✅ Preparação Inicial

O site terá como tema focas e outros animais. Primeiro, foi criada a estrutura
básica do projeto:

- Pasta "projeto-pratico"
- Arquivo index.html
- Pastas "img" e "video" para assets
- Arquivo style.css

Foi utilizado o formato BEM para nomear as classes CSS, que significa:

- Block 
- Element
- Modifier
  
Esse formato ajuda a organizar o CSS de forma mais limpa e fácil de entender.

O site conta com uma página longa, com várias seções, cada uma com uma
classe diferente. As principais são:

- Hero section (sessão inicial, de destaque)
- Section comum
- Gallery (galeria de imagens)
- Footer
- Depois do HTML, foram adicionadas as imagens e o vídeo que serão utilizados.

## ✅ Estilização Inicial

No arquivo style.css, primeiro foram feitos alguns ajustes iniciais:

- *{ margin: 0; padding: 0; 
- box-sizing: border-box;}
- :root { color-background: #030207; --color-white: #FFFFFF; --color-blue: #474BFF;}
- body { background-color: var(--color-background); 
- color: var(--color-white); }
- a { color: var(--color-blue); }

Isso define o tema escuro do site, com cores branca e azul, além de normalizar os
estilos padrão do navegador.

## ✅ Hero Section

Começando a estilização seção por seção, primeiramente foi trabalhada a hero
section, que é a sessão de destaque inicial do site.

## ✅ Hero Background

O elemento de fundo é um vídeo, então primeiro o tamanho foi ajustado:

- .hero-background { width: 100%; height: 100vh; object-fit: cover;
-  position: relative;
-  z-index: -10;}

A propriedade define como um elemento se encaixa no local onde está. No caso,
foi usado para o vídeo cobrir toda a área disponível. object-fit cover

Foram usados para posicionar o vídeo atrás dos outros
elementos. position z-index

Por fim, um degradê transparente para escurecer o vídeo na parte inferior:

- .hero { background: linear-gradient(rgba(0,0,0,0.1), var(--colorbackground)); min-height: 100vh;}

## ✅ Hero Foreground

O elemento foreground contém o título e texto por cima do vídeo. Foi centralizado
e estilizado:

- hero-foreground { color: var(--color-white); 
- text-align: center;
- margin-top: 40vh;}
- .hero-title { font-size: 5rem; 
- font-weight: 300; 
- text-transform: uppercase; 
- letter-spacing: .5rem; }



LINKEDIN: [Felipe_Souza](https://www.linkedin.com/in/felipe-souza-devweb/)



  
