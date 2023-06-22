# Aula 13 - Git Stash: Guardando alterações temporariamente

O Git Stash é uma ferramenta útil para guardar alterações não commitadas temporariamente. Ele permite que você reverta suas alterações sem perdê-las, possibilitando retomar seu trabalho posteriormente.

## Motivação para usar o Git Stash

- Impedir merge ou publicação de alterações incompletas ou instáveis.
- Tentar forçar atualização com pull/push quando há alterações locais.
- Fazer checkout de uma branch com alterações não commitadas.

## Comandos do Git Stash

- `git stash`: guarda as alterações no stash.
- `git stash pop`: recupera as alterações do stash e remove-as do stash.
- Mais informações podem ser encontradas neste [artigo sobre o Git Stash](https://opensource.com/article/21/4/git-stash).

## Fluxo de ações utilizando o Git Stash

1. Guardando alterações em uma branch:
   - Realize suas alterações na branch 1.
   - Execute `git stash` para guardar as alterações no stash.
   - Faça `git pull` para atualizar a branch.
   - Utilize `git stash pop` para recuperar as alterações do stash.

2. Guardando alterações e alternando entre branches:
   - Realize suas alterações na branch 1.
   - Execute `git stash` para guardar as alterações no stash.
   - Faça checkout para a branch 2 e faça suas modificações, faça commit e push.
   - Volte para a branch 1 utilizando o checkout e execute `git stash pop` para recuperar as alterações do stash.

O Git Stash é uma ferramenta útil para guardar temporariamente as alterações não commitadas e permitir uma troca de contexto mais fácil durante o desenvolvimento.
