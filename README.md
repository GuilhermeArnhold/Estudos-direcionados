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
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Bem vindo!</h1>
    </head>
    <body>
        conteúdo
    </body>
</html>
```
* `<html>`: Todo documento html é inserido dentro desta tag, quando finalizado ela é fechada. Ou seja, ela contém todos os outros elementos dentro dela. 
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Html</h1>
    </head>
    <body>
        Este site foi criado para teste.
    </body>
</html>
```
* `<head>`: É inserido entre a tag html e a do body, contém dentro dela metadatas que podem definir o titulo do documento, o estilo e scripts.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Calculadora</h1>
    </head>
    <body>
        <h2>Bem vindo usuário</h2>
        <p>Criei este site para você calcular.</p>
    </body>
</html>
```
* `<title>`: Insere um título ao documento, deve ser somente texto. É mostrado na aba da página, é necessário em documentos html. As recomendações são que não seja longo, algo entre uma ou duas palavras de tamanho entre 50 e 60 caracteres.  
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <h2>Testando</h2>
        <p>Este site foi criado para teste.</p>
    </body>
</html>
```
* `<body>`: Define o corpo do documento, contém outras tags do html como headings, paragraphs, images, hiperlink,tables,lists.
 ```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p><a href="Google.com">Conheça nosso site.</a></p>
        <h2>Testando</h2>
        <p>Este site foi criado para teste.</p>
        <h3>Olá</h3>
    </body>
</html>
```
* `<h1>` to `<h6>` : Definem os títulos, sendo 1 o principal e diminui sua relevancia conforme aumenta seu número, ou seja 6 o menos relevante ou um subtítulo. Apenas um h1 pode ser usado por página deve-se observar a hierarquia afim de uma boa estruturação e uso dessas tags.
 ```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <h2>Titulo 2</h2>
        <h3>Titulo 3</h3>
        <h4>Titulo 4</h4>
        <h5>Titulo 5</h5>
        <h6>Titulo 6</h6>
    </body>
</html>
```

* `<p>`: Define um parágrafo, o navegador adiciona uma linha em branco antes de cada elemento p.
 ```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>Um parágrafo.</p>
        <p>Outro parágrafo</p>
    </body>
</html>
```
* `<br>`: Insere uma quebra de linha, é uma tag que não tem fechamento.
 ```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>Bem</p><br><p>Vindo</p>
    </body>
</html>
```
* `<hr>`: É uma "linha" que separa conteúdos ou define uma mudança em documentos HTML.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p> HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.. 
        </p>
    </body>
</html>
```
* `<!-->`...`<-->`: Utilizada para inserir comentários, não são exibidos nos navegadores. É possível utilizar para comentar seu código e pode ajuda-lo em outro momento quando você for editar seu código.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p> HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        </p>
    </body>
</html>
```
* `<abbr>`: Define uma abreviação ou acrônimo quando passado o mouse sobre o elemento.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p> HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML. 
        </p>
        <abbr title = "World Wide Web">WWW</abbr> commonly know as the Web.
    </body>
</html>
```
* `<adress>`: Utilizado para informar o contato do autor/criador do documento ou artigo, o contato pode ser o endereço de email, URL, número do telefone...
Esse elemento geralmente está em itálico e os navegadores sempre adicionarão uma quebra de linha antes e depois de cada elemento adress.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p> HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.. 
        </p>
        <abbr title = "World Wide Web">WWW</abbr> commonly know as the Web.
        <address>
            Escrito por: Guilherme.
            Telefone: 99999999
            Cidade: São Paulo - Brasil
        </address>
    </body>
</html>
```
* `<adress>`: Transforma o texto em negrito. Deve ser utilizado como ultimo recurso, quando nenhuma outra tag é apropriada.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        </p>
        <abbr title = "World Wide Web">WWW</abbr> commonly know as the Web.
        <b>Texto em negrito</b>
        <address>
            Escrito por: Guilherme.
            Telefone: 99999999
            Cidade: São Paulo - Brasil
        </address>
    </body>
</html>
```
* `<bdi>`: Não é suportado em todos os navegadores, é mais utilizado no caso de línguas árabes nas quais possuem a escrita de trás para frente.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        </p>
        <abbr title = "World Wide Web">WWW</abbr> commonly know as the Web.
        <b>Texto em negrito</b>
        <address>
            Escrito por: Guilherme.
            Telefone: 99999999
            Cidade: São Paulo - Brasil
        </address>
        <ul>
            <li>Usuário João: 60 pontos</li>
            <li>Usuário<bdi>Maria</bdi>: 80 pontos</li>
            <li>Usuário <bdi>إيان</bdi>: 90 pontos</li>
        </ul>
    </body>
</html>
```
* `<bdo>`: Substitui a direção do texto(inverte).
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        </p>
        <abbr title = "World Wide Web">WWW</abbr> commonly know as the Web.
        <b>Texto em negrito</b>
        <address>
            Escrito por: Guilherme.
            Telefone: 99999999
            Cidade: São Paulo - Brasil
        </address>
        <ul>
            <li>Usuário João: 60 pontos</li>
            <li>Usuário<bdi>Maria</bdi>: 80 pontos</li>
            <li>Usuário <bdi>إيان</bdi>: 90 pontos</li>
            <bdo dir="rtl"> Texto </bdo>
        </ul>
    </body>
</html>
```
* `<cite>`: Define o título de um trabalho criativo como um livro, um poema, um som... O nome de uma pessoa não é um título de um trabalho, o texto dentro da tag fica em itálico.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        </p>
        <p><cite>The movie</cite> by Guilherme Arnhold.</p>
    </body>
</html>
```
* `<code>`: Essa tag é utilizada para inserir trechos de código.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        </p>
        <p><cite>The movie</cite> by Guilherme Arnhold.</p>
        <code>background-color</code>
    </body>
</html>
```
* `<del>`: Define o texto deletado do documento, os navegadores geralmente inserem uma linha sobre esse texto.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML (abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        <p> Eu gosto de <del>ler</del> <ins>música.</ins>
        </p>
    </body>
</html>
```
* `<dfn>`: Especifica um termo que será definido com o conteúdo. O pai mais proximo do dfn deve conter a explicação/definição do termo.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML(abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        <p> 
            <dfn>WWW</dfn>Significa em português rede de alcance mundial, também conhecida como Web ou WWW. World Wide Web é um sistema de documentos em hipermídia que são interligados e executados na Internet.
        </p>
    </body>
</html>
```
* `<em>`: É utilizada para enfatizar/destacar um texto. o conteúdo é transformado para itálico.

```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML(abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        <p>We need <em>you</em></p>
    </body>
</html>
```
* `<i>`: Frequentemente utilizado para indicar um termo técnico, uma frase de outra língua, um nome de um návio... É utilizado quando nenhum outro elemento é apropriado, o texto é transformado em itálico.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML(abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        <p>We need <em>you</em></p>
    </body>
</html>
```
* `<ins>`: Insere um texto no documento, os navegadores geralmente sublinham o texto inserido. É utilizado junto com a tag del.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <!--
        Este é um comentário.
        -->
        <p>Bem</p><br><p>Vindo</p>
        <hr>
        <p>HTML(abreviação para a expressão inglesa HyperText Markup Language, que significa Linguagem de Marcação de Hipertexto) é uma linguagem de marcação utilizada na construção de páginas na Web. Documentos HTML podem ser interpretados por navegadores. A tecnologia é fruto da junção entre os padrões HyTime e SGML.
        <p>We need <em>you</em></p>
        <p>O site é <del>velho</del> <ins>novo</ins>
    </body>
</html>
``` 
* `<kbd>`: É usado para para definir uma entrada de teclado.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>Bem</p><br><p>Vindo</p>
        <p>Utilize <kbd>Ctrl</kbd> + <kbd>A </kbd>para selecionar tudo.</p>
    </body>
</html>
``` 
* `<mark>`: Marca/destaca um texto.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
    To Buy
        <ul>
            <li>
            <mark>Café</mark><br>
            </li>
            <li>
            <mark>Leite</mark><br>
            </li>
            <li>
            <mark>Frutas</mark>
            </li>
        </ul>
    </body>
</html>
```
* `<meter>`: Realiza uma medição de uma faixa conhecida. Não deve ser utilizada para mostrar o progresso, para isso temos a tag progress.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <label for="disk_c">Disk usage C:</label>
        <meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter>
    </body>
</html>
```
* `<pre>`: Define um texto pré formatado, com fonte de largura fixa preservando os espaços e quebras de linhas. O texto é exibido exatamente como no código fonte html.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <pre>O texto é formatado    exatamente como no código fonte html.
        </pre>
    </body>
</html>
```
* `<progress>`: Deve ser adicionado com a tag label para melhor visualização e acessibilidade. Representa o progresso de uma determinada tarefa.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <label for="file">Progresso:</label>
        <progress id="file" value="32" max="100"> 32% </progress>
    </body>
</html>
```
* `<q>`:É utilizado para citações curtas, coloca o texto em aspas.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <q>O que não provoca minha morte faz com que eu fique mais forte.</q>
    </body>
</html>
```
* `<rp>`: É utilizado junto com ruby para mostrar textos em navegadores que não suportam ruby, esse elemento insere parênteses ao redor do texto.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <ruby>
                漢<rt><rp>(</rp>ㄏㄢˋ<rp>)</rp></rt>
            </ruby>
        </p>
    </body>
</html>
```
* `<rt>`: É utilizado junto com o elemento ruby e rp, define uma explicação ou pronuncia de caracteres do leste asiático.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <ruby>
                漢<rt><rp>(</rp>ㄏㄢˋ<rp>)</rp></rt>
            </ruby>
        </p>
    </body>
</html>
```
* `<ruby>`: Essa tag especifica uma anotação ruby. Uma anotação ruby é um texto pequeno, anexado ao texto principal para indicar a pronuncia ou significado dos caracteres. É frequentemente usado em publicações japonesas.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <ruby>
                漢<rt><rp>(</rp>ㄏㄢˋ<rp>)</rp></rt>
            </ruby>
        </p>
    </body>
</html>
```
* `<s>`: Especifica um texto que não é mais correto, algo que não se aplica mais(que se modificou). O texto será tachado com uma linha.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <s>Bolas de futebol por apenas 50 reais.</s>
            Acabou, não temos mais disponível!
        </p>
    </body>
</html>
```
* `<samp>`: Define um texto como a saída de um programa de computador em um documento, o navegador exibe na fonte monoespaçada padrão.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <s>Bolas de futebol por apenas 50 reais.</s>
            Acabou, não temos mais disponível!
        </p>
    </body>
</html>
```
* `<small>`: Define um texto pequeno.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <small> Este é um pequeno texto</small>
        </p>
    </body>
</html>
```
* `<strong>`: Define um texto importante, o navegador destaca o texto em negrito. Para um texto sem importância se usa a tag b.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            <strong>Cuidado com o cão!</strong>
        </p>
    </body>
</html>
```
* `<sub>`: Define um texto subscrito com uma fonte pequena. 
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            Dióxido de carbono<sub>CO2</sub>
        </p>
    </body>
<html>
```
* `<sup>`: Define um texto sobrescrito que aparece com uma fonte pequena.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>
            World Wide Web<sup>WWW</sup>
        </p>
    </body>
</html>
```
* `<template>`: Usado com javascript, permite esconder um conteúdo ao carregar a página.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
    <button onclick="showContent()">Show hidden content</button>

        <template>
            <h2>Flower</h2>
            <img src="img_white_flower.jpg" width="214" height="204">
        </template>

        <script>
            function showContent() {
            var temp = document.getElementsByTagName("template")[0];
            var clon = temp.content.cloneNode(true);
            document.body.appendChild(clon);}
        </script>
    </body>
</html>
```
* `<time>`: Define um horário e uma data, é utilizado para que os navegadores possam adicionar lembretes de datas por meio do calendário do usuário.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p> Eu tenho uma festa para ir
        <time datetime="2020-10-24 10:00"> no dia das crianças.
        </time>
        </p>
    </body>
</html>
```
* `<u>`: Representa um texto não articulado com estilo diferente do texto normal, geralmente palavras com erros ortográficos ou nomes proprios em chinês. O conteúdo dentro da tag u, é sublinhado pelo navegador.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>não<u>mecha</u></p>
    </body>
</html>
```
* `<var>`: Define uma variavel em um programa ou uma expressão matematica. O conteúdo fica em itálico.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p><var>b</var> x <var>a</var> = 5</p>
    </body>
</html>
```
* `<wbr>`: Especifica onde em um texto poderia adicionar uma quebra de linha. Quando uma linha é muito longa, o navegador quebra automaticamente e pode quebrar em um lugar incorreto. Por isso, usa-se o wbr.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p>This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.</p>
        <p><b>Note:</b> The wbr element is not supported in Internet Explorer 11 (or earlier).</p>
    </body>
</html>
```
* `<form>`: É utilizada para criar uma formulário html para entradas do usuário.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <form action="/action_page.php" method="get">
            <label for="fname">First name:</label>
            <input type="text" id="fname" name="fname"><br><br>
            <label for="lname">Last name:</label>
            <input type="text" id="lname" name="lname"><br><br>
            <input type="submit" value="Submit">
            </form>
    </body>
</html>
```
* `<input>`: Especifica onde o usuário pode inserir dados, é o elemento mais importante do form element.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <form action="/action_page.php">
            <label for="nome">Nome:</label>
            <input type="text" id="fname" name="nome"><br><br>
            <label for="sobrenome">Sobrenome:</label>
            <input type="text" id="lname" name="sobrenome"><br><br>
            <input type="submit" value="Submit">
        </form>
    </body>
</html>
```
* `<textarea>`: É utilizado para definir uma inserção de texto maior pelo usuário, como para coletar comentários.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <textarea id="linguaPortuguesa" name="linguaPortuguesa" rows="5" cols="50">
            A Língua Portuguesa é falada tanto em Portugal, quanto no Brasil e em outros diversos países ao redor do planeta. Assim sendo, falar este idioma pode abrir uma série de oportunidades  pessoais e até mesmo profissionais.
        </textarea>
    </body>
</html>
```
* `<button>`: Cria um botão para interação com o usuário.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <button type="button"> Clique aqui!</button>
    </body>
</html>
```
* `<select>`: Cria uma caixa de seleção com varias opções a serem escolhidas.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <label for="cor">Escolha uma cor:</label>
        <select name="cor" id="cor">
        <option value="branco">Branco</option>
         <option value="verde">Verde</option>
        <option value="laranja">Laranja</option>
        <option value="preto">Preto</option>
  </select>
    </body>
</html>
```
* `<optgroup>`: Separa em grupo as opções da caixa de seleção, utilizado junto com a tag select. Quando há um grande numero de opções os grupos facilitam para maneja-las.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <label for="camisa">Escolha uma camisa:</label>
        <select name="camisas" id="camisas">
            <optgroup label ="Grêmio">
                <option value="geromel">Camisa 3 - Pedro Geromel </option>
                <option value="kannemann">Camisa 4 - Walter Kannemann</option>
            </optgroup>
            <optgroup label ="Barcelona">
                <option value="messi">Camisa 10 - Lionel Messi</option>
                <option value="coutinho">Camisa 14 - Phillipe Coutinho</option>
            </optgroup>
        </select>
    </body>
</html>
```
* `<option>`: Define uma opção em uma lista de seleção. Geralmente utilizada junto com a tag select.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <label for="camisa">Escolha uma camisa:</label>
        <select name="camisas" id="camisas">
            <option value="geromel">Camisa 3 - Pedro Geromel </option>
            <option value="kannemann">Camisa 4 - Walter Kannemann</option>
         </select>
    </body>
</html>
```
* `<label>`: Cria um rótulo para os elementos
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <p> Escolha a cor desejada: </p>
        <label for="cor">Cor:</label>
        <input type="color" name="cordacamisa"  id="cor">
    </body>
</html>
```
* `<fieldset>`: Desenha uma caixa em volta dos elementos, agrupa os elementos em um formulário.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <fieldset>
            <legend>Formulario</legend>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome"><br><br>
            <label for="sobrenome">Sobrenome:</label>
            <input type="text" id="sobrenome" name="sobrenome"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
            <label for="telefone">Telefone:</label>
            <input type="telefone" id="telefone" name="telefone">
        </fieldset>
    </body>
</html>
```
* `<legend>`: Cria uma legenda para a tag fieldset.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <fieldset>
            <legend>Formulario</legend>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome"><br><br>
            <label for="sobrenome">Sobrenome:</label>
            <input type="text" id="sobrenome" name="sobrenome"><br><br>
        </fieldset>
    </body>
</html>
```
* `<datalist>`: Cria uma lista com opções pré definidas.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <label for="esportes">Escolha seu esporte:</label>
        <input list="esportes" name="esporte" id="esporte">
        <datalist id="esportes">
            <option value="Futebol">
            <option value="Volei">
            <option value="Handebol">
            <option value="Natação">
            <option value="Atletismo">
        </datalist>
    </body>
</html>
```
* `<output>`: É utilizado para representar o resultado de um cálculo.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <form oninput="x.value=parseInt(a.value)+parseInt(b.value)">
        <input type="range" id="a" value="50">
        +<input type="number" id="b" value="25">
        =<output name="x" for="a b"></output>
        </form>
    </body>
</html>
```
* `<iframe>`: Cria um quadro, um frame. É utilizado para incorporar outros documentos a um documento HTML. É uma boa prática incluir um atributo titulo para o frame.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
      <iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>
    </body>
</html>
```
* `<img>`: Insere uma imagem em uma página HTML, a imagem não é inserida na página e sim vinculada a ela. Esse elemento necessita dois outros elementos, o SRC que especifica o caminho da imagem e o alt que descreve a imagem caso ela não puder ser exibida.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
       <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600"> 
    </body>
</html>
```
* `<map>`: Define um mapa de imagem, ou seja, uma imagem com áreas clicáveis.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
      <img src="workplace.jpg" alt="areadetrabalho" usemap="#workmap" width="400" height="379">
        <map name="workmap">
            <area shape="rect" coords="34,44,270,350" alt="computador" href="computer.htm">
            <area shape="rect" coords="290,172,333,250" alt="telefone" href="phone.htm">
            <area shape="circle" coords="337,300,44" alt="xicara de café" href="coffee.htm">
        </map>
    </body>
</html>
```
* `<canvas>`: É utilizado para desenhar gráficos por meio de scripts, a tag é transparente e é apenas um container para gráficos, é necessário um script para desenhar os gráficos. Mesmo que o navegador não suporte a tag canvas e o javascript esteja desabilitado o conteúdo será exibido.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <canvas id="myCanvas">
            Seu navegador não suporta a tag canvas
        </canvas>
        <script>
            var canvas = document.getElementById("myCanvas");
            var ctx = canvas.getContext("2d");
            ctx.fillStyle = "#black";
            ctx.fillRect(0, 0, 100, 100);
        </script>
    </body>
</html>
```
* `<figcaption>`: Define uma legenda para uma imagem.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <figure>
            <img src="https://i2.wp.com/marketingcomcafe.com.br/wp-content/uploads/2017/12/banco-imagens-gratis.png" alt="homemprotestando" style="width:100%">
            <figcaption>Fig 1 - Um homem de máscara protestando.</figcaption>
        </figure>
    </body>
</html>
```
* `<figure>`: Especifica conteúdo independente como fotos, diagramas, ilustrações...
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <figure>
            <img src="https://i2.wp.com/marketingcomcafe.com.br/wp-content/uploads/2017/12/banco-imagens-gratis.png" alt="homemprotestando" style="width:100%">
            <figcaption>Fig 1 - Um homem de máscara protestando.</figcaption>
        </figure>
    </body>
</html>
```
* `<picture>`: Oferece maior flexibilidade para manipular imagens, podendo aumentar ou diminuir a imagem conforme a janela de visualização. A tag picture contém a tag source e img.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <picture>
            <source media="(min-width:650px)" srcset="https://i2.wp.com/marketingcomcafe.com.br/wp-content/uploads/2017/12/banco-imagens-gratis.png">
            <source media="(min-width:465px)" srcset="http://www.fundosanimais.com/imagens-imagens-lobos-jpg">
            <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
        </picture>
    </body>
</html>
```
* `<svg>`: Cria um container para gráficos vetoriais escalonaveis. Ou seja, é possível desenhar formas.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <svg width="400" height="180">
        <rect x="50" y="20" rx="20" ry="20" width="150" height="150" style="fill:red;stroke:black;stroke-width:5;opacity:0.5" /></svg>
     </body>
</html>
```
* `<audio>`: É usado para inserir som ao documento, o texto dentro da tag audio só é exibido quando o navegador não suportar a tag audio, esse elemento possui uma ou mais tags source.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <audio controls>
            <source src="audio.ogg" type="audio/ogg">
            <source src="audio.mp3" type="audio/mpeg">
            Seu navegador não suporta o elemento audio.
        </audio>
     </body>
</html>
```
* `<source>`: Com ela é possível especificar ao navegador arquivos alternativos conforme sua janela de visualização ou suporte, o navegador irá escolher a primeira source compatível.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <audio controls>
            <source src="audio.ogg" type="audio/ogg">
            <source src="audio.mp3" type="audio/mpeg">
            Seu navegador não suporta o elemento audio.
        </audio>
     </body>
</html>
```
* `<track>`: Especifica faixas de texto para as tags audio ou video, é usado para especificar legendas ou outros arquivos contendo texto que devem ser visiveis durante a reprodução.
```html
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <video width="320" height="240" controls>
            <source src="forrest_gump.mp4" type="video/mp4">
            <source src="forrest_gump.ogg" type="video/ogg">
            <track src="fgsubtitles_en.vtt" kind="legendas" srclang="en" label="English">
            <track src="fgsubtitles_no.vtt" kind="legendas" srclang="no" label="Norwegian">
        </video>
     </body>
</html>
``` 
* `<video>`: Usado para inserir video em um documento, essa tag contém um ou mais tag sources e o navegador escolhe a primeira que possui suporte. O texto entre a tag e o seu fechamento apenas é exibido quando o navegador não suportar essa tag.
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <title>Html 5</title>
        <h1>Estudando</h1>
    </head>
    <body>
        <video width="320" height="240" controls>
            <source src="https://www.w3schools.com/tags/movie.mp4" type="video/mp4">
            <source src="https://www.w3schools.com/tags/movie.ogg" type="video/ogg">
            Seu navegador não suporta a tag de video.
        </video>
     </body>
</html> 
``` 

