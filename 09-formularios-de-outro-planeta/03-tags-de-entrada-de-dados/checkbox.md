# Input do tipo checkbox: `<input type="checkbox">`

- Caixas que podem ser marcadas
- Selecionar um valor para ser enviado
- Se não selecionado, não será enviado nenhum dado

## Atributos

- Globais
- Value:
    * valor que aquele campo contém
    * se não estiver presente, o padrão é 'on'
- Checked
    * para deixar o campo marcado por padrão

## Outras observações

- ### Podemos marcar múltiplos valores

- Usaremos o atributo 'name' com o mesmo nome para os diversos campos, exemplo:

```
    <fieldset>
        <legend>Choose your interests</legend>
            <div>
                <label for="coding">Coding</label>
                <input 
                    type="checkbox" 
                    id="coding" 
                    name="interest"
                    checked
                    >
            </div>
            <div>
                <label for="music">Music</label>
                <input 
                    type="checkbox"
                    id="music"
                    name="interest"
                    value="music"
                >
            </div>
    </fieldset>
```