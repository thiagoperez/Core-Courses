# Funções

1. Introdução

    - Pode-se definir uma sub-rotina como um bloco de comandos, como um sub-algoritmo;
    - O uso de sub-rotinas permite organizar, estruturar e modularizar o algoritmo.
        
        - Subdividir um problema e sua soluções em partes coerentes;
        - Evita-se redundância de código;
        - Facilita a leitura e diminui a complexidade.
    
    - Exemplo: Automóvel

        - Sistema de direção;
        - Sistema de frenagem;
        - Sistema de injeção;
        - Motor;
        - Chassis;
        - Partes externas.

2. Funções intrínsecas

    - Existem funções "pré-programadas" às quais chamamos de funções intrínsecas.
    - São exemplos de funções intrínsecas:

        - escreva() - saída de dados na tela;
        - escreval() - saída de dados na tela com quebra de linha;
        - leia() - entrada de dados via teclado;
        - raizq() - cálculo da raiz quadrada;
        - rand() - gera um número real aleatório.

3. Funções

    - Funções podem ter nenhum, uma, ou várias entradas (parâmetros).
    - Toda função possui um tipo de retorno:

        - Uma função é obrigada a produzir um resultado através do comando retorne.
    
    - Toda função é declarada com um nome próprio.
    
        - Para utilizar a função, deve-se chamá-la (invocá-la) pelo nome.
        - Informar seus argumentos (parâmetro reais).
    
    - Exemplo de função: função raizq()

        - Parâmetros: número real.
        - Retorno: número real.

        Algoritmo "invocandoFuncao"
        Var
            param, retorno: real
        Inicio
            escreval("Insira o valor: ")
            leia(param)
            retorno <- raizq(param)
            escreval("Resultado: ", retorno)
        Fimalgoritmo

4. Criando uma função nova

    - Caso precise de uma função que ainda não exista, você deve criar a sua própria.
    - Para criar uma função, precisa-se:
        
        1. Prover um nome à função;
        2. Estabelecer os parâmetros formais(entradas) - Variáveis locais com nome e tipo;
        3. Programar os passos que a função deverá executar;
        4. Estabelecer o(s) valor(es) de retorno(saída)
        5. Sintaxe de declaração de uma função:

            Funcao <nome>([<parâmetros>]) : <tipo-retorno>
                [Var <variáveis-locais>]
            Inicio
                <bloco-de-comandos>
                retorne <valor-retorno>
            Fimfuncao
        
        6. Exemplo de função nova
            - Criar e invocar uma função capaz de calcular o resultado de um número real elevado ao cubo.

            Algoritmo "novaFuncao"
            Var
                param, retorno: real
            
            Funcao cubo(x: real) : real
                Var resultado: real
            Inicio
                resultado <- x*x*x
                retorne resultado
            Fimfuncao

            Inicio
                escreval("Insira o valor: ")
                leia(param)
                retorno <- cubo(param)
                escreval("Resultado: ", retorno)
            Fimalgoritmo

5. Escopo de variáveis

    - Dependendo do lugar no qual uma variável foi declarada, ela pode ter visibilidade restrita.

        - Variáveis globais: declaradas no corpo principal do algoritmo. 
            
            - Acessível em qualquer ponto do algoritmo.

        - Variáveis locais: declaradas dentro de uma sub-rotina.
            
            - Acessíveis apeans dentro daquela sub-rotina.
            - Em tempo de execução: só é criada quando a sub-rotina é invocada e destruída logo em seguida.