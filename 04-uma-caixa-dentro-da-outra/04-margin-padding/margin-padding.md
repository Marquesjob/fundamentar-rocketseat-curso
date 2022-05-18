## Margin

Espaços entre os elementos

- margin-top | margin-right | margin-bottom | margin-left
- values:    `<lenght>` | `<percentage>` | auto

```css 
div {
    /* shorthand */
    margin: 12px 16px 10px 4px; /* top, right, bottom, left*/
    margin: 12px 16px 0; /* top, sides, bottom*/
    margin: 8px 16px; /* top/bottom, sides */
    margin: 8px; /* the same value is applied on all sides */
}

```

* Cuidado com margin collapsing (top se ajunta ao bottom)

## Padding

Preenchimento interno da caixa

- padding-top | padding-right | padding-bottom | padding-left
- values: `<length>` | `<percentage>` | auto

```css
div {
    /* shorthand */
    padding: 12px 16px 10px 4px;
    padding: 12px 16px 0;
    padding: 8px 16px;
    padding: 8px; 
}
```

    *padding poderá causar diferença na largura de um elemento