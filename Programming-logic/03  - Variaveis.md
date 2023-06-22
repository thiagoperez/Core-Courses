# Variáveis

1. As variáveis permitem armazenar e acessar uma informa durante a execuão de um algoritmo.
    - Velores armazenados em memória.
    - Os valores podem ser alterados conforme a necessidade e a lógica do algoritmo.
    - Pseudocódigo: declaradas no comando: VAR

2. Toda variável possui
    - Um tipo;
    - Um nome.

3. Nomes de variáveis
    - Nunca começam com um número;
    - Geralmente começam com uma letra ou underline;
    - Podem conter letras, underline e números, desde que o número não seja o primeiro caractere;
    - Não admite espaços;
    - Não admite acentos e caracteres especiais.

    Exemplos: peso, Altura, numero2, _mValor, valor_unitatio, A.
    
    Exemplos falsos: 2nome, caso de teste, *a, peso&altura.

4. Tipos de Dados
    - O tipo de uma variável é definida pelo seu conteúdo.
    - Uma variável que armazena um número do conjunto dos inteiros é do tipo inteiro;
    - Uma variável que armazena um número do conjunto dos reais é do tipo real ou flutuante;
    - Uma variável que armazena um valor verdadeiro ou falso é do tipo logico ou booleano;
    - Uma variável que armazena uma ou mais letra é considerada do tipo caractere.

5. Atribuição
    - A atribuição é uma operação para armazenar um dado ou alterar o conteúdo de uma variável.
    - Símbolo em pseudocódigo: <- .
    - Símbolo em fluxogramas: = .

    Exemplos de Atribuição
     - num1               <-                   10;
     - peso               <-                 50.5;
     - letra2             <-                  "A";
     - flag               <-                falso;
     - centimetros        <-         metros * 100;
     - area               <-           3.14 * R^2;
     - nome               <- "Pietro" + "Martins";
     - mensagem           <-        "Erro fatal!";
     - expressao_logica   <-               10 > 5;

6. Funcionalidades de uma variável
    - Para que servem as variáveis?
    - Cria um espaço em memória para poder trabalhar nos dados do algoritmo;
    - Armazenar valores informados pelo usuário;
    - Armazenam os resultados de expressões aritméticas e lógicas;
    - Armazenam os valors de entrada ou de saída de uma função.

    Exemplo:
    Algoritmo "somar"
    Var
        numeroA, numeroB, resultado: inteiro
    Inicio
        leia(numeroA)
        leia(numeroB)
        resultado <- numeroA + numeroB
        escreva(resultado)
    fimalgoritmo

7. Erros comuns envolvendo variáveis
    - Escrever o nome da variável errado
    
        Algoritmo "erroComum1"
        Var
            peso: real
        Inicio
            peso <- 50.5
            escreva(Peso)
        Fimalgoritmo

    - Usar uma variável que não foi criada

        Algoritmo "erroComum2"
        Var
            num: inteiro
        Inicio
            num1 <- 10
            num1 <- num1 + soma
        Fimalgoritmo








