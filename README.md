# Estudos
## O que são linguagens de marcação?
* É um sistema moderno para anotação de um texto de modo que ele seja sintaticamente distinguível
* Elas são utilizadas para definir formatos,maneiras de exibição e padrões em um documento.
* Normalmente, não possuem estruturas de controle.
* Elas utilizam marcadores ou tags, o sistema identifica a tag e reconhece de que modo exibir o conteúdo.
## Quais as mais comuns?
* São elas, HTML,XHTML,SGML e XML.
## Onde são usadas?
* São usadas na industria editorial para marcar a formatação, porém, pode ser usada para criar sites, documentos, textos, livros e mensagens. 
## Exemplo de códigos HTML
```html 
<!DOCTYPE HTML>
<html lan ="pt-br">
    <head>
        <title>GitHub</title>
        <h1>Bem vindo ao site!</h1>
    </head>
    <body>
        <h2> Guilherme Arnhold </h2>
        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
    </body>XML
</html>
```
## Exemplo de códigos XML
```xml
<?xml version="1.0"?>
<mensagem>
    <para> João </para>
    <de> Maria </de>
    <titulo>Horario do trem</titulo>
    <texto>Olá, o trem passará às 15h, não esqueça.</texto>
</mensagem> 
```
## HTML 5 Tags
* `<!DOCTYPE>`: Todo arquivo html deve iniciar com essa declaração, não é uma tag do HTML e tem como função informar ao browser sobre qual tipo de documento que se trata.
*Exemplo:
```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Bem vindo!</h1>
    <\head>
    <body>
        conteúdo
    </body>
<\html>
```
* `<html>`: Todo documento html é inserido dentro desta tag, quando finalizado ela é fechada. Ou seja, ela contém todos os outros elementos dentro dela. 
```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Html</h1>
    <\head>
    <body>
        Este site foi criado para teste.
    </body>
<\html>
```
* `<head>`: É inserido entre a tag html e a do body, contém dentro dela metadatas que podem definir o titulo do documento, o estilo e scripts.
```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Calculadora</h1>
    <\head>
    <body>
        <h2>Bem vindo usuário</h2>
        <p>Criei este site para você calcular.</p>
    </body>
<\html>
```
* `<title>`: Insere um título ao documento, deve ser somente texto. É mostrado na aba da página, é necessário em documentos html. As recomendações são que não seja longo, algo entre uma ou duas palavras de tamanho entre 50 e 60 caracteres.  
```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    <\head>
    <body>
        <h2>Testando</h2>
        <p>Este site foi criado para teste.</p>
    </body>
<\html>
```
* `<body>`: Define o corpo do documento, contém outras tags do html como headings, paragraphs, images, hiperlink,tables,lists.
 ```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    <\head>
    <body>
        <p><a href="Google.com>Conheça nosso site.</a></p>
        <h2>Testando</h2>
        <p>Este site foi criado para teste.</p>
        <h3>Olá</h3>
    </body>
<\html>
```
* `<h1>` to `<h6>` : Definem os títulos, sendo 1 o principal e diminui sua relevancia conforme aumenta seu número, ou seja 6 o menos relevante ou um subtítulo. Apenas um h1 pode ser usado por página deve-se observar a hierarquia afim de uma boa estruturação e uso dessas tags.
 ```
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    <\head>
    <body>
        <h2>Titulo 2</h2>
        <h3>Titulo 3</h3>
        <h4>Titulo 4</h4>
        <h5>Titulo 5</h5>
        <h6>Titulo 6</h6>
    </body>
<\html>
```
