# Aula 10: Pull Requests - Solicitando Inclusão de Código

## Na décima aula, o professor Pietro Martins de Oliveira abordou o tema "Pull Requests - Solicitando Inclusão de Código" no Git. Veja os principais pontos discutidos

1. Controle do código em sua branch:
   - Ao enviar seu código para sua branch, ele está sob seu controle.

2. Contribuição por meio de Pull Requests:
   - Ao solicitar a mesclagem de sua branch com a branch do time, você está contribuindo com o código dos outros.

3. Motivação para Pull Requests:
   - A motivação por trás dos Pull Requests é convidar pessoas para revisar seu código ou revisar o código de alguém.

## Repositórios públicos vs. privados

1. Repositórios privados:
   - Em repositórios privados, você cria uma branch "short-lived" a partir da branch de desenvolvimento e, em seguida, faz um Pull Request.

2. Repositórios públicos:
   - Em repositórios públicos, você faz um fork (clone) do repositório original e, em seguida, faz um Pull Request.

## Fluxo de Ações em Pull Requests

1. Código -> git add -> git commit -> git push -> Pull Request

## Code Review

1. Aspectos considerados em uma revisão de código:
   a. Boas práticas.
   b. Convenções do time de desenvolvimento.

2. Resolução de sugestões feitas por revisores:
   - GitHub Web:
     - Comentários.
     - Commits com ajustes.
   - Processo de revisão e ajustes (ping-pong) até que todos estejam satisfeitos e o merge seja aceito.

## Fluxo de Ações em Code Review

1. Pull Request
   -> Revisor 1: Comentários
      -> Resposta & Commits
         -> Revisor 2: Comentários
            -> Respostas & Commits
               -> Revisor 2: Comentários
                  -> (Revisor 3: Pull Request Aceito ou Revisor 3: Pull Request Negado)
