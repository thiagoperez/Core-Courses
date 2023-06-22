# Matrizes

1. Introdução

    - Aplicações com tabelas são inerentemente matriciais.

        - Solução: MATRIZES.
    
    - Definição matemática: uma matriz bidimensional é um arranjo tabular de MxN valores, onde M é o número de linhas e N é o número de colunas.

    - Os elementos de uma matriz são acessados por dois índices:

        . i - geranmente associado às linhas.
        . j - geralmente associado às colunas.
    
    - Definição algorítmica: matrizes são estruturas de dados multidimensionais que necessitam de mais de um índice para serem manipuladas.

        - Referenciada pelo mesmo nome;
        
        - Podem ter 2, 3 ... K índices;
        
        - Matrizes mais comuns: bidimensionais;
        
        - Em uma matriz MxN:
        
            - Índices variam de 1 a M e de 1 a N.

2. Sintaxe de declaração de uma matriz

    <nome_m>: Vetor[<1..d1>,<1..d2>,...,<1..dn>] de <tipo>

    Exemplo de criação de uma matriz bidimensional:
    
    Mat: Vetor[1..3, 1..3] de inteiro

3. Sintaxe de acesso a uma posição

    <nome_da_matriz>[<índ1>,<índ2>,...,<índN>]

    - Exemplo de acesso a elementos da matriz

        - Mat[1,1]; |1 2 3|
        - Mat[3,3]; |4 5 6|
        - Mat[1,3]; |7 8 9|
        - Mat[2,1]; 

4. Exemplo

    - Desenvolver um algoritmo que crie uma matriz 3x3 de números inteiros. O algoritmo deverá inicializar cada uma das posições da matriz com os números de 1 a 9, conforme a matriz a seguir, sem que o usuário seja solicitado a inserir os valores.

        |1 2 3|
        |4 5 6|
        |7 8 9|

        Algoritmo "criaMatriz"
            Var mat: Vetor[1..3, 1..3] de inteiro
                i, j, cont: inteiro
        Inicio
            cont <- 1
            para i de 1 ate 3 passo 1 faca
                para j de 1 ate 3 passo 1 faca
                    mat[i,j] <- cont
                    cont <- cont + 1
                fimpara
            fimpara
        Fimalgoritmo
            