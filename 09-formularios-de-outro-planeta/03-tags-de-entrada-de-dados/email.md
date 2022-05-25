# Email input: `<input type="email">`

* Espera que o usuário digite um E-mail
* Irá verificar se o valor digitado é um E-mail

## Atributos

* placeholder
* readonly / disabled
* value
* required
* multiple
    - o campo irá receber 1 ou mais E-mails, separado por vírgulas
* minlength / maxlength
    - O mínimo e/ou máximo valor que o campo irá conter
* size 
    - Valor númerico indicado quantos caracteres esse
* pattern 
    - Uso de expressão regular para validar o campo 
    - exemplo: o usurário só poderá colocar email do domínio
      rocketseat.com.br
        - `pattern="[.+@rocketseat\.com\.br]"`
* list 
    - o ID de uma tag `<datalist>` que está  no mesmo documento
    - `<datalist>` irá conter uma lista de valores pré definidos
      a fim de sugerir ao usuário, quais valores estão disponíveis
      - Os valores do `<datalist>` que não forem compativeis com o
        campo, não serão apresentados como sugestão