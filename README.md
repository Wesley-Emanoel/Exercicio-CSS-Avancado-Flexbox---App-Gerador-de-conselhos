# Exercício HTML + CSS Avançado - Parte 1 - Gerador de conselhos

Descrição da tarefa: Você deve criar um layout próximo desse desafio do frontend mentor: [Frontend Mentor | Advice generator app coding challenge](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db). Onde o principal desafio é construir um aplicativo que gere conselhos aleatórios. Nessa primeira etapa do exercício, será realizado apenas a construção do HTML e CSS.


### Capturas de telas

![Captura de tela desktop](./src/imagems-minha-resolucao/Captura%20de%20tela%20desktop.png)
![Captura de tela desktop hover](./src/imagems-minha-resolucao/Captura%20de%20tela%20desktop%20hover.png)
![Captura de tela mobile](./src/imagems-minha-resolucao/Captura%20de%20tela%20mobile.png)

## Meu progreço

### Construido com

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### O que eu aprendi
Aprendi sobre a tag picture com sourse:

```html
<picture>
  <source srcset="./src/images/pattern-divider-mobile.svg" media="(max-width: 600px)"/>
  <img src="src/images/pattern-divider-desktop.svg" alt="pattern" />
</picture>
```

Aprendi sobre como personalizar a tag button.
```html
<button class="botao" type="button" onclick="alert ('Novo Conselho')"><img src="src/images/icon-dice.svg" alt=""></button>
```
```css
.botao {
    height: 50px;
    width: 50px;
    background-color: hsl(150, 100%, 66%);
    border-radius: 50px;
    position: relative;
    bottom: 25px;
}

button:hover{
    box-shadow: 0 0 10px 0 hsl(150, 100%, 66%) inset, 0 0 10px 4px hsl(150, 100%, 66%);
    cursor: pointer;
}
```

### Desenvolvimento contínuo

Pretendo continuar me aprimorando na edição dos layots usando o css e  no uso das tags no html.


### Recursos úteis

- [Edição do botão](https://www.brasilcode.com.br/35-botoes-css-com-animacao/) - Essa página me ajudou com a edição do houver do botão. 
- [Uso da tag picture](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source) - Essa página me auxiliou na implementação das imagens responsivas.

## Autores

- Website - [Curso dev em dobro](https://cursos.devemdobro.com)

- Frontend Mentor - [frontendmentor](https://www.frontendmentor.io/challenges/advice-generator-app-QdUG-13db)
