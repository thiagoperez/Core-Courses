# Formas de Representações

1 - O que fazer dentro de um algoritmo convencional?
 a. Delimitar o início e o fim do algoritmo;
 b. Reservar espaçoes de trabalho em menória (variáveis);
 c. Realizar entrada e/ou saída de dados;
 d. Efetuar operações matemáticas;
 e. Armazenar ou modificar valores salvos em memória;
 f. Tomar decisões com base em condições;
 g. Criar ou invocar funções (subalgoritmos).

2 - Formas de representação de algoritmo
 a. Linguagem natural?;
 b. Fluxogramas;
 c. Linguagem estruturadas:
    - Pseudocódigo (Portugol);
    - Linguagem de programação.

3 - Linguagem natural
 a. Não queremos ambiguidade.
    - "Carlos pediu a José para assinar o contrato." (Quem vai assinar, Carlos ou José?).
    - A égua da minha vizinha é linda! (A vizinha é uma "égua" linda, pu a égua que pertence à vizinha é que é linda?).

4 - Floxogramas
    - Representação visual de um algoritmo
   IMAGEM

5 - Fluxograma: somar dois números
 IMAGEM
 - Início do algoritmo;
 - Entrada de dados;
 - Alteração de conteúdo na memória (variável S);
 - Saída;
 - Fim.

6 - Fluxograma: média entre dois números
 IMAGEM

7 - Pseudocódigo
 a. Liguagem estruturada para representar uma sequência lógica de passos não-ambígua;
  - Sintaxe (regras) - Normalmente o copilador já acusa de immediato;
  - Semântica (Lógica) - Normalmente o erro só aparece após execução do código.

8 - Elementos do pseudocódigo
 a. Tipos de dados
    - Inteiro;
    - Real;
    - Caractere;
    - Lógico.
 b. Constantes & Literais
    - Valores que não se alteram.
 c. Variáveis
    - Valores que podem se alterar.
 d. Atribuição
    - "<-".
 e. Operadores Aritméticos
    - Soma: +;
    - Subtração: -;
    - Multiplicação: *;
    - Divisão: /;
    - Resto de divisão (módulo): MOD ou %;
    - Potenciação: ^.
 f. Operadores Lógicos
    - nao;
    - e;
    - ou;
    - xou.
 g. Entrada e saída de dados
    - leia();
    - escreva();
    - escreval().
 h. Estrutura de decisão
    - se ... então;
    - se ... então ... senão;
    - escolha ... caso ... .
 i. Estrutura de repetição
    - para ... ;
    - enquanto ... ;
    - repita ... .
 j. Procedimentos & funções

9. Pseudocódigo: média entre dois números
    Algoritmo "calcularMedia"
    var
        n1, n2, media: real
    inicio
        escreval("Insira o primeiro valor: ")
        leia(n1)
        escreval("Insira o segundo valor: ")
        leia(n2)
        media <- (n1 + n2) / 2
        escreval("O resultado é: ")
        escreva(media)
    fimalgoritmo