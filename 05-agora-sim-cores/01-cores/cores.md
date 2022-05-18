## Cores 

Usamos CSS para alterar cores do nosso documento.

## Tipos 

* background-color (para caixas)
* color -> para textos 
* border-color -> para caixas
* outros...

## Valores 

Podemos definir os valores por

* palavra chave (blue, transparent)
* hexadecimal (#0)
* funções: rgb, rgba, hsl, hsla

```css

element {

    /* Keyword values */
    color: currentcolor;

    /* <named-color values> */
    color:red;
    color:orange;
    color: tan;
    color: rebeccapurple;

    /* <hex-color> values 0-F */
    color: #090; /* RED GREEN BLUE */
    color: #009900;
    color: #090a;
    color: #009900aa;

    /*<rgb()> values*/
    color: rgb(34, 12,64, 0.6);
    color: rgba(34, 12,64, 0.6);
    color: rgb(34 12 64 / 0.6);

    /* <hsl()* values */
    color: hsl(34, 12,64, 0.6);
    color: hsla(34, 12,64, 0.6);
    color: hsl(34 12 64 / 0.6);

    /* Global values */
    color: inherit;  /* herda a cor do elemento anterior*/
    color: initial;  /* volta a cor para a inicial */
    color: unset;   /* pega a cor do contexto */

}

```