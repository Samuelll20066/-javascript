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
// comentário de linha 
~~~
~~~ javascript
/* comentário de bloco simples */
~~~
~~~ javascript
/**
 * comentário de bloco com marcador 
 */
~~~
