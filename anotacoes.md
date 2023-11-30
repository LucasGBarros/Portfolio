## Anotações sobre HTML + CSS

## Tópico I - Entendendo elementos do HTML
    
    > DOCTYPE HTML - É uma declaração que define que o documento é HTML;
    > html - É o elemento raiz de uma página em HTML;
    > head - É onde esta meta informações sobre o próprio documento na página HTML;
    > title - É o elemento que especifica o título da página.
    > body - Elemento que define o corpo do documento;
    > h1 - Elemento que define titulo grande
    > p - Elemento que define um parágrafo
    > img - propriedade inserção de imagem, propriedade pode ser o caminho no caso src="imagem.png"
    > img propriedade alt="nome da imagem" - Se refere ao nome da imagem, caso não carregue visualmente.
    > lang="pt-br" - Elemento de linguagem do projeto
    > charset="UTF-8" - Unicode de caracteres
    > name="viewport" content="width=device-width, initial-scale=1.0" - dispositivo que esta acessando a pagina e a escala e largura baseada que esta sendo aberto o projeto
    > a - Tag Âncora
    > a href="https://" - serve para inserir link de referência

## Tópico II - Estrutura de HTML para criação de uma página

    > !DOCTYPE html> 
    > html lang="pt-br">
    > head>
    >    meta charset="UTF-8">
    >    meta name="viewport" content="width=device-width, initial-scale=1.0"
    >    title>Nome do Projeto /title>
    >   /head>
    > body>
    >    header>/header> Menu/ Cabeçalho
    >    main>/main> Conteúdo principal
    >    footer>/footer> Rodapé da página    
    > /body>
    > /html>

## Tópico III - Entendendo CSS

    > link - vincular o style.css com o HTML
    > rel - que indica qual a relação do documento HTML com o outro que trataremos que no caso será a stylesheet "folha de estilo" e inserindo href que no caso seria referência do arquivo
    > body - campo de corpo onde iremos manipular o layout da página 
        > background-color - cor de fundo
        > color - cor de texto
            > Dentro de color, podemos inserir palavras chaves de cores, inserindo um caracter especial "#" + paleta de cor
    > margin - margem do site, recebendo o valor = 0, ele nao tem margem
    > padding - antes do campo body, temos um campo chamado padding que remete ao preenchimento de cada elemento.
    > heigth - Definindo altura do site = 100vh (vh = viewport heigth) ou seja, utilizando 100% da tela
    > box-sizing - remete que a imagem, ou algum campo deva ficar dentro do elemento pai, neste caso "body"
    > flexbox - ele colocará os elementos no sentido de linha, porém, é algo configurado e pode estar como coluna. Conhecido com Flex-direction.
    > align-items - alinhamento de linhas, onde compõe alguns elementos como flex-start | flex-end | center e afins.
    > section - criando uma seção separada da imagem.
    > width - definindo largura do texto 
    > font-size - Tamanho do título ou tamanho de texto
    > font-family - Fonte importada sendo utilizada no elemento font-family.