# Input do tipo radio: `<input type="radio">`

- Projetado para selecionar uma única opção de um grupo de opções

## Atributos essenciais

- Checked:
    * indica que o campo foi marcado
- Value:
    * valor que aquele campo contém

## Exemplo de usabilidade:

```
<fieldset>
    <legend>Bora tomar um café?</legend>
    
    <label for="yep">Sim</label>
    <input type="radio" id="yep" name="coffee" value="yes">

    <label for="nope">Não</label>
    <input checked type="radio" id="nope" name="coffee" value="no">
</fieldset>
```