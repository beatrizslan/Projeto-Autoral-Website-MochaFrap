# Autoral - Desenvolvimento do Projeto Website MochaFrap | Coffee

Desenvolvimento próprio do design e codificação do projeto website [MochaFrap](https://beatrizslan.github.io/Projeto-Website-Vegan/).

## Indíce

Visão Geral | [Desafio](#desafio) | [Screenshot](#screenshot) | [Links](#links)
---|---|---|---

Meu Processo | [Construído com](#construído-com) | [O que eu aprendi](#o-que-eu-aprendi) | [Recursos úteis](#recursos-úteis)
---|---|---|---

Considerações Finais | [Autor](#autor)
---|---

## Visão Geral

### Desafio

O desafio foi construir este projeto por inteiro, incluindo o design e layout. Os usuários devem ser capazes de:

- Vizualizar o layout ideal tanto para dispositivos mobiles quanto para desktops;
- Vizualizar os estados de foco para elementos interativos. 

### Screenshot

![Foto MochaFrap](https://user-images.githubusercontent.com/105252003/178911630-a1dd8f42-f372-4b9b-b673-056d0ee25364.jpg)

### Links

- URL da solução: [Index](https://github.com/beatrizslan/Projeto-Website-Coffee/blob/main/docs/index.html)
- URL do site: [Site](https://beatrizslan.github.io/Projeto-Website-Coffee/)

## Meu processo

### Construído com

- HTML5 com tags semânticas;
- Propriedades personalizadas de CSS;
- Flexbox;
- Media-queries;
- Mobile first.

### O que eu aprendi

- Linkar fontes externas;
- Utilizar variáveis no CSS;
- Trabalhar com o flexbox;
- Desenvolver uma página responsiva, com mobile first.

```HTML
 <link rel="preconnect" href="https://fonts.googleapis.com">
 <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
 <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
```

```CSS
:root {
  --fonte-principal: "Roboto";
}

body {
  font-family: var(--fonte-principal);
}

.produto__icones {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}
  
@media screen and (min-width: 1024px) {}
```

### Recursos úteis

- [Guia Completo do Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Este é um artigo incrível que me ajudou a entender melhor de como funciona o Flexbox e quais são suas propriedades. 
- [Media Queries](https://css-tricks.com/snippets/css/media-queries-for-standard-devices/) - Este é um outro artigo do mesmo autor que também foi muito importante para eu ter uma melhor noção sobre as dimensões de telas dos dispositivos móveis.
  

## Considerações Finais

### Autor

- Website - [Beatriz Slan](https://beatrizslan.github.io/Projeto-Website-Coffee/)
- Linkedin - [in/beatriz-slan](https://www.linkedin.com/in/beatriz-slan-2324a4173/)
