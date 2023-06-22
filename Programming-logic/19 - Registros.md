# Registros

1. Introdução

    - Os tipos primitivos não serão eficientes em todas as situações. Existem alguns casos que são necessários outros tipos mais avançados.

    - Um controle de estoque de produtos por exemplo precisa de:

        - Armazenas váris informações.

        - Código, nome do produto, quantodade em estoque, valor de compra, valor de venda, lucro, observações sobre o produto.
    
    - Os Registros são estruturas de Dados Heterogêneas.

    - Também conhecidas como registros, tipos de dados compostos ou estruturas.

    - Agrupam informações de tipos de dados diferentes.

    - Trata um grupo de valores como sendo uma única variável com vários campos distintos.

    - Resumindo: cria-se um novo tipo de dados.

2. Exemplo: Controle de estoque

    - Código: número inteiro;
    - Nome do produto: texto(caractere);
    - Quantidade estocada: número real;
    - Valor da compra: número real;
    - Valor de venda: número real;
    - Lucro: número real;
    - Observações do produto: texto(caractere).

3. Sintaxe de definição de um novo registro

    Tipo
        <identificador> = registro
        <lista dos campos e seus tipos>
    Fimregistro

    - Identificador: nome do novo tipo.
    - Lista de campos: relação dos campos que compõem o novo tipo.

    Algoritmo "exemploRegistros"
        Tipo
            produto = registro
            codigo: inteiro
            nome: caractere
            quantidade: inteiro
            valor: real
        Fimregistro
    Var
        p1: produto
    Inicio
        escreva("Digite o código: ")
        leia(p1.codigo)
        escreva("Insira o valor: ")
        leia(p1.valor)
        escreva("Digite o nome: ")
        leia(p1.nome)
        escreva("Insira a contidade: ")
        leia(p1.quantidade)
    Fimalgoritmo

4. Registro + Vetores

    - O exemplo anterior trata apenas um produto. Como criar uma lista de produtos?

    - Registros podem ser combinados com vetores:

        1. Decrara-se um novo registro.
        2. Cria-se um vetor de registro(assim como se cria variável  de tipo registro).

5. Exemplo

    - Considerando uma aplicação de controle de estoque, crie um algoritmo para que seja possível armazenar as seguintes informações sobre dez produtos, utilizando vetor de registros:

        - Código do prouto;
        - Nome do produto;
        - Quantidade do produto em estoque;
        - Valor unitário do produto.

        Algoritmo "exemploRegistros"
            Tipo
                produto = registro
                codigo: inteiro
                nome: caractere
                quantidade: inteiro
                valor: real
            Fimregistro
        Var
            lista_prod: Vetor[1..10] de produto
            i: inteiro
        Inicio  
            para i de 1 ate 10 passo 1 faca
                escreva("Digite o código ", i, ": ")
                leia(lista_prod[i].codigo)
                escreva("Insira o valor ", i, ": ")
                leia(lista_prod[i].valor)
                escreva("Digite o nome ", i, ": ")
                leia(lista_prod[i].nome)
                escreva("Insira a quantidade ", i, ": ")
                leia(lista_prod[i].quantidade)
            fimpara
        Fimalgoritmo
    