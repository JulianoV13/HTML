# Estudo html
## O que é html ?
    - É uma linguagem de marcas, em que seu código não é compilado, pelo contrário
    ele é interpretado e renderizado por meio de um moto web que faz a exibição dos 
    elementos html em formato gráfico.
        - Renderizar: pegar o código e transformar em elemento gráfico
        - Motor Web: é uma ferramenta do navegador responsavel por "ler" o código html, realizar 
        a "comparação e/ou busca" na biblioteca de comando do navegador e realizar o proceso 
        de renderização
## A signa HTML
    - HT -> hypertext (hiper texto)
    - M -> markup (marcas | marcação)
    - L -> language (linguagem)
    - Comandos para serem processados no formato de midia

## Como usar o html
    - Para usar os comandos html é necessário escreve-lo usando tags(palavras-chave);
        Tags(comandos | palavra-chave) podem ser compostas(casadas) ou simpls(solteiras)
            -Tag composta é o comando que inicia e precisa ser finalizando para determinar
            sua abrangencia de execução. Por exemplo: <body>....</body> | <strong> ... </strong>
            - Tag simples: são comandos que não precisam ser finalizados, apenas aplica-se
            Exemplo: <br>...<img>...<meta>...<link>

## As tags html podem ter atributos
    - Atributos são qualificadores para uma tag html. Eles podem adicionar recursos a mais para a
    tag. Exemplo: <img src="foto.jpg" alt="foto">. No exemplo anterior a tag se chama-se img ou 
    atributos são: 
        - src ( source = origem) determina a imagem que será exibida. Aqui, você deve 
        passar o caminho da imagem 
        - alt(alternate = alternativo) determina um texto que será exibido quando a imagem não carrega
        e é utilizado pelo leitor de tela(screen reader) para deficientes visuais

    Outro exemplo: <form action="cadastro.php" method="post"> .... </form>
        a tag form é composta e também pode ter atributos. Quando for finalizar a tag composta 
        não será necessário colocar os atributos no fechamento. Você deve fechar somente a tag
        No exemplo acima temos:
            Tag form -> criar o escopo do formulário
            atributo action -> indica caminho para onde os dados do formulário irão
            atributo method -> indica o método como os dados serão enviados

## Estrutura básica de uma página html

``` 
    <html>
        <head>
        <meta charset=UTF-8>
        <title> Primeira página </title>
        </head>
        <body>
            <h1> Primeira página </h1>
    <html> 
``` 