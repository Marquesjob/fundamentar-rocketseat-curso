## font-variant

* variações na apresentação da fonte

```css
p {
    font-variant: small-caps;
}
```
-------------------------------------------------

## letter-spacing

* Espaços entre caracteres

```css
p {
    letter-spacing: 4px;
}
```
-------------------------------------------------
## text-transform

* Transformação do texto

```css
p {
    text-transform: uppercase;  /*capitalize | lowercase | none*/
}
```
-----------------------------------------------
## line-height

* Espaços entre linhas
* Pode ser com unidades ou sem unidades de medida
* Comuns: 1.5 ou 2

```css
p {
    line-height: 1.6;
}
```
-----------------------------------------------
## text-decoration

* Aparencia decorativa de um texto
* line: underline | overline | line-through
        * Podemos aplicar mais de um valor.
* style: wavy | dotted | double | dashed | solid
* color: `<color>` values

```css
p {
    text-decoration: underline;
}
```
-----------------------------------------------

## text-align

* Alinhamento de um texto

```css
p {
    text-align: center;
}
```
----------------------------------------------

## text-shadow

* Sombra aplicada a um texto
* Permite múltiplos valores

```css
p {
    text-shadow: 1px 1px 1px red,
                 2px 2px 1px green; /*offset-y | offset-y | blur-radius | color */
}
```
---------------------------------------------

## Shorthand 

* font-style, font-variant, font-weight, font-stretch, font-size, line-height, e font-family

```css
p {
    font: italic normal bold normal 3em/1.5 Helvetica, Arial, sans-serif;
}
```




