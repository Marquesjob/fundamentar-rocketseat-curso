# Input do tipo URL: `<input type="url">`

- Espera que o usuário digite uma url
- Irá verificar se o valor digitado é uma url

## Atributos:

- placeholder
- readonly / disabled
- value
- required
- minlength / maxlength
- size:
    * O mínimo e/ou valr que o campo irá conter
- Uso de expressão regular para validar o campo
- list:
    * O ID de uma tag `<datalist>` que está no mesmo documento
    * `<datalist>` irá conter uma lista de valores pré definidos a fim de
    sugerir ao usuário, quais valores estão disponíveis
        * Os valores do `<datalist>` que nao forem compatíveis com o campo,
        não serão apresentados como sugestão
- spellcheck
    * Habilitar a verificação ortográfica para este input
