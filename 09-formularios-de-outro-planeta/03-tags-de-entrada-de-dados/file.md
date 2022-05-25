# Input do tipo file: `<input type="file">`

- Usuário poderá escolher 1 ou mais arquivos para enviar no formulário

## Atributos

- value:
    * contém o arquivo a ser enviado
- accept:
    * descreve que tipos de arquivos serão aceitos
    * exemplo: .doc, .docx, .pdf, .audio/*, image/png, .png
- files: 
    * a lista de arquivos ou arquivo.
- multiple
    * permite o envio de múltiplos arquivos

## Envio de arquivos

- Para envio dos arquivos o formulário deverá utilizar método POST e o atributo enctype com "multipart/form-data"

