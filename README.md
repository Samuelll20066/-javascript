# Fundamentos do Javascript Clássico 

## INTEGRAÇÕES

### Integrar Javascript de forma interna 

~~~ html
./index.html

 <!DOCTYPE html>
    <html lang="pt-BR">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Javascript</title>
        </head>
        <body>
            <script>
                console.log("Hello world!")
            </script> 
        </body>
    </html>
~~~

### Integrar Javascript de forma externa 

- Criar diretório ***src*** na raiz do projeto
- Criar arquivo ***script.js*** na raiz do diretório ***src***
- Integrar de forma externa o arquivo ***script.js*** no arquivo ***index.html***

~~~ html
./index.html

<!DOCTYPE html>
    <html lang="pt-BR">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Javascript</title>
        </head>
        <body>
            <script>
                console.log("Hello world!")
            </script> 
        </body>
    </html>
~~~

## COMENTÁRIOS 

### Comentário de linha

~~~ javascript
./.src/script.js
// comentário de linha 
~~~
~~~ javascript
./.src/script.js
/* comentário de bloco simples */
~~~
~~~ javascript
./.src/script.js
/**
 * comentário de bloco com marcador 
 */
~~~

## VARIÁVEIS 

### Declaração 

~~~ javascript
./.src/script.js

var number;

~~~

### Atribuiçao de valor 

~~~ javascript
./.src/script.js

var number;

number = 5;

~~~

### Declaração e atribuição de valor 

~~~ javascript
./.src/script.js

number = 5;

~~~

### Reatribuição de valor 

~~~ javascript
./.src/script.js

number = 5;

number = 10;

~~~
