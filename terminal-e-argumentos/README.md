## Executando arquivo .class pelo CMD:

## Executar o java.class dentro da pasta bin:

### Terminal:

abrir o cmd e acessar o local que está o arquivo .class

Linhas de códigos:

Ir até o diretório do arquivo.class
cd C:\Users\Pichau\eclipse-workspace\AppCalculadora\bin<br>
dir - é usado para exibir uma lista de arquivos e pastas em um diretório específico<br>
cls - é usado para limpar a tela do terminal, removendo todo o conteúdo anteriormente exibido na janela do console.<br>

### executando programa no terminal:
java Calculadora<br>

### Argumentos

Quando executamos uma classe, que contenha o método main, o mesmo permite que passemos um array [] de argumentos, do tipo String. Logo, podemos após a definição da classe a ser executada, informar estes parâmetros

## Passando argumentos através do launch.json

[![image](https://user-images.githubusercontent.com/122856066/235833358-e055be94-27fc-4b91-8c36-7f8264b51c0f.png)](https://glysns.gitbook.io/java-basico/sintaxe/terminal-e-argumentos)


Exemplo: <br>

        {
            "type": "java",
            "name": "AboutMe",
            "request": "launch",
            "mainClass": "AboutMe",
            "projectName": "terminal-e-argumentos_a9520479",
            "args": [
                "CAIO",
                "BELLO",
                "30",
                "1.72"
            ]
        },
        
        
        

## Scanner

Nos exemplos anteriores, percebemos que podemos receber, dados digitados pelo usuário do nosso sistema, porém, tudo precisa estar em uma linha e também é necessário informar os valores nas posições correspondentes. Esta abordagem pode deixar margens de execução, com erro do nosso programa. Para isso, com a finalidade de deixar as nossas entradas de dados mais seguras, agora vamos receber estes dados via Scanner.

[![image](https://user-images.githubusercontent.com/122856066/235833503-81914cad-0db4-4910-897d-bf48bf760b0f.png)](https://glysns.gitbook.io/java-basico/sintaxe/terminal-e-argumentos)
