# Recursividade

1. Introdução

    - Definição: O conceito de recursividade está relacionado a algo que pode ser definido em termos de si próprio.

    - Em programação: recursividade é um mecanismo que permite a função chamar a si mesma direta ou indiretamente.

    - Concretizando: Relação de parentesco(pais x filhos):
    
        1. Pai;
        2. Avô - Pai do meu Pai;
        3. Bisavô - Pai do meu Avô: Pai do Pai do meu Pai.
        4. Trisavô - Pai do meu Bisavô: Pai do Pai do Pai do meu Pai.

    - O princípio da recursividade consiste em diminuir um problema, sucessivamente, em problemas menores.

    - De tanto diminuir o problema, chega-se a um ponto em que o problema pode ser resolvido diretamente(por definição).

    - Depois, combinam-se as soluções!

    - Uma função recursiva precisa ter duas partes:

        - Caso base: verifica-se que o problema está no menor tamanho possível(não é possível diminuir mais).

            - Solução direta.

        - Chamada recursiva: faz-se uma nova chamada da função transformando o problema atual num problema menor.

2. Exemplo

    - A função Fatorial: na matemática, a função fatorial de um número n, onde n E Z+, é o resultado do produto de todos os inteiros positivos que são menores ou iguais ao próprio n.

        - Ou seja:

            - n! = n x (n-1) x (n-2) x ... x 3 x 2 x 1.
        
        - Exemplo:

            5! = 5 x 4 x 3 x 2 x 1 = 120.
    
    - Fatorial:

        - 0! = 1(por definição);
        - 1! = 1(por definição);
        - 2! = 2 x 1 = 2;
        - 3! = 3 x 2 x 1 = 6;
        - 4! = 4 x 3 x 2 x 1 = 24;
        - 5! = 5 x 4 x 3 x 2 x 1 = 120.

        - É possível definir o fatorial de um número n como sendo o próprio número n multiplicado pelo fatorial do seu antecessor, n-1.

            n! = n x (n-1)!

        - 0! = 1(por definição);
        - 1! = 1(por definição);
        - 2! = 2 x 1!;
        - 3! = 3 x 2!;
        - 4! = 4 x 3!;
        - 5! = 5 x 4!.

        Obs.: Infelizmente o professor não ensinou as funções.

        Funcao fat(n: inteiro) : inteiro
        Inicio
            Se (n = 0) ou (n = 1) entao
                retorne 1
            Senao
                retorne n * fat(n-1)
            Fimse
        Fimfuncao

-> Fim do curso. Se até aqui chegou, recomendo fazer diversos exercícios para assimilar os conteúdos das aulas e posteriormente estudar Estrutura de Dados.

    