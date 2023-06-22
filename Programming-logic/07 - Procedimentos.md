# Procedimentos

1. Introdução

    - Assim como uma função, um procedimento é um sub-algoritmo.
        
        - Bloco de comandos.
    
    - Também possui os seguintes elementos

        - Nome;
        - Variáveis locais;
        - Início;
        - Procedimento;
        - Fim.

2. Diferença: Procedimento x Funções

    - Procedimentos não têm um tipo;
    - Retornar um valor não é obrigatório.
    - Sintaxe:

        Procedimento <nome>([<parâmetros>])
            Var <variáveis-locais>
        Inicio
            <bloco-de-comandos>
        Fimprocedimento

3. Criando um procedimento

    - Desenvolver um procedimento algorítmico que seja capaz de converter uma quantia de dinheiro em reais para seu valor correspondente em dólares americanos. O usuário deve ser solicitado a informar a a quantia que pretende converter, em reais, bem como a cotação do dia. O procedimento deve informar o resultado da conversão em dolares.

    Algoritmo "conversaoMoeda"
        Var
            qtde, cotacao: real
        Procedimento converte(r: real; c: real)
            Var d: real
        Inicio
            d <- r/c
            escreval("Você tem ", d, " dólares)
        Fimprocedimento
    Inicio
        escreval("Insira a quantidade em reais: ")
        leia(qtde)
        escreval("1 dólar custa quantos reais?")
        leia(cotacao)
        converte(qtde, cotacao)
    Fimalgoritmo

4. Passagem de parâmetros

    - Será que parâmetros servem apenas para realizar entrada de dados em uma sub-rotina?
      
        - É possível definir um parâmetro formal de forma a permitir que ele possa realizar entrada quanto saída de dados.
    
    - Passagem de parâmetros:
    
        - por valor - não se altera o parâmetro real;
        - por referência - parâmetro real é alterado.
            - Desenvolver um procedimento algorítmico que seja capaz de converter uma quantia de dinheiro em reais para seu valor correspondente em dólares americanos. O usuário deve ser solicitado a informar a quantia que pretende converter, em reais, bem como a cotação do dia. O procedimento deve retornar o resultado da conversão em dólares.
            
            Algoritmo "conversaoMoeda"
                Var
                    qtde, cotacao: real
                Procedimento converte(Var din: real; c: real)
                Inicio
                    din <- din/c
                Fimprocedimento
            Inicio
                escreval("Insira a quantidade em reais: ")
                leia(qtde)
                escreval("1 dólar custa quantos reais?")
                leia(cotacao)
                converte(qtde, cotacao)
                escreval("Você tem ", qrde, " dólares")
            Fimalgoritmo
