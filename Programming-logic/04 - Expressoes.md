# Expressões

1. Expressões Aritméticas
    - Apresentam um resultado numérico como saída;
    - Forma de realizar cálculos com números inteiros e reais;
    - Manipular valores por meio de operadores matemáticos;
    - Operações básicas: adição(+), subtração(-), multiplicação(*), divisão(/), resto da divisão inteira(%), potenciação(^), radiciação(sem símbolo).

2. Operações Aritméticas

    .Em pseudocódigo:             |  .Expressões matemáticas:
    - Resultado <- 10 +9          |  - 10+9=19
    - num1 <- 10-9*3              |  - 10-9x3=-17
    - teste <- 3*4^2/2            |  - 3x4²÷2=24
    - var1 <- 7*(2+3)-2           |  - 7x(2+3)-2=33
    - expressao <- 0.5*2+1        |  - 0,5x2+1=2
    - Y <- 7/2                    |  - 7÷2=3,5
    - X <- 2+Raizq(9)             |  - 2+√9=5

3. Outros operadores

    - Divisão inteira(DIV): resulta no valor inteiro de uma divisão entre dois números inteiros
        . X <- 10 DIV 3
        . 10 ÷ 3 = 3

        . Y <- 8 DIV 2
        . 8 ÷ 2 = 4
    
    - Módulos(MOD): retorna o resto de uma divisão entre dois números
        . X <- 10 MOD 3
        . 10 / 3 = 3
        . 10 - (3 * 3) = 1

        . Y <- 8 MOD 2
        . 8 / 2 = 4
        . 8 - (2 * 4) = 0

4. Expressões relacionais

    - Apresentam um resultado booleano como resposta(verdadeiro ou falso).
    - Processar valores numéricos por meio de operadores relacionais:
     . Maior que:        >
     . Maior ou igual a: >=
     . Menor que:        <
     . Menor ou igual a: <=
     . Igual a:          =
     . Diferente de:     <>

5. Expressões Lógicas

    - Uma brave introdução à lógica proporcional...
    - Proposições: sentença declarativas denotadas por letras(p,q,r...)
    - Proposições possuem um valor verdade: verdadeiro ou falso.
    - Exemplo: O Brasil é um país sul-americano.

6. Operações Lógicas

    - Negação(não) - Inverte o valor lógico.
        Símbolos: não,¬,~,not
        Exemplo: p="O Brasil é hezacampeão"
        Tabela verdade da negação:
            p | ¬q
            V | F
            F | V

    - Conjunção(e) - Operação  E Lógica.
        Só é verdadeiro cado ambos os operadores valerem verdadeiro.
        Se um dos operadores for false, o resultado será false.
        Simbolos: e,^,&,&&,and
        Exemplos: p="Touxe ovos"; q="Trouxe leite".
        Tabela verdade da conjunção:
            p | q | p^q
            V | V | V
            V | F | F
            F | V | F
            F | F | F

    - Disjunção(ou) - Operação OU lógica.
        Só é falso caso ambos os operandos valerem falso.
        Se um dos operandos for verdadeiro, o resultado é verdadeiro.
        Símbolos: ou,v,||,+,or.
        Exemplo: p="Trouxe suco"; q="Trouxe refrigerante".
        Tabela verdade da disjunção: 
            p | q | p v q
            V | V |   V
            V | F |   V
            F | V |   V
            F | F |   F

    - Disjunção exclusiva(xou): Operação OU Exclusivo
        Só é falso caso ambos os operadores valerem o mesmo valor lógico.
        Só é verdadeiro caso ambos os operadores valerem um valor lógico distinto.
        Símbolos: xou,xor.
        Exemplo: p="Ela trabalha"; q="Ela cuida das crianças".
        Tabela verdade da disjunção exclusiva:
            p | q | p xou q
            V | V |    F
            V | F |    V
            F | V |    V
            F | F |    F

7. Prioridades de Operações

    a. Operações Aritméticas
        1. Parênteses;
        2. Potenciação & Rediciação;
        3. Multiplicação & Divisão;
        4. Soma & Subtração.
    
    b. Operações relacionais

    c. Operações lógicas(booleanas)
        1. Parênteses;
        2. Inversão;
        3. Conjunção;
        4. Disjunção.