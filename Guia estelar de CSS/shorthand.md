# Shorthand

* Junção de propriedades
* Resumido
* Legível

```css
{
    /* background properties*/
    background-color: #000;
    background-image: url(images/bg.gif);
    background-repeat: no-repeat;
    background-position: left top;

    /* backgroud shorthand*/
    background: #000 url(images/bg.gif) no-repeat left top;

    /* font properties*/
    font-style: italic;
    font-weight: bold;
    font-size: .8em;
    line-height: 1.2;
    font-family: Arial, sans-serif;

    /* font shorthand*/
    font: italic bold .8em/1.2 Arial, sans-serif;
}

```

## Detalhes

* Não irá considerar propriedades anteriore
* Valores não específicados irão assumir valores padrão
* Geralmente, a ordem descrita não importa , mas, se houver muitas propriedades com valores semelhantes, podemos encontrar problemas.

## Propriedades que aceitam Shorthand

animation, background, border, border-bottom, border-color, border-left, border-radius, border-style, border-top, border-width, column-rule, columns, flex, flex-flow, font, grid, grid-area, grid-column, grid-row, grid-template, list-style, margin, offset, outline, overflow, padding, place-content, place-items, plade-self, text-decoration, transition

**https://developer.mozilla.org/pt-BR/docs/Web/CSS/Shorthand_properties**