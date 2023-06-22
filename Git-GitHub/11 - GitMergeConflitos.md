# Aula 11: Git Merge & Conflitos: Integrando código e resolvendo conflitos

## 1. O que são conflitos?

- É natural ter problemas ao mesclar códigos escritos por pessoas distintas.
- Dois commits distintos realizados em um mesmo arquivo, em uma mesma linha de código.
- Exemplos de comandos que podem gerar conflitos: merge, rebase, pull, stash, apply... o próprio pull request pode gerar conflito!

## 2. Como resolver conflitos?

- Escolher manter uma ou outra alteração.
- Escolher inserir as duas alterações (a ordem importa).
- Remover ambas alterações.
- Cancelar o merge.

## 3. Fluxo de ações: Merge e Conflitos

Pull Request

1. Sem Comflito: Code Review -> (Revisor: PR Aceito ou Revisor: PR Negado).
2. Com Conflitos: Solução de conflitos -> Code Review -> (Revisor: PR Aceito ou Revisor: PR Negado)

## 4. Mantendo minha branch atualizada

- Merge de branch de desenvolvimento para minha branch.
- Opções para solução dos eventuais conflitos:
  - Sozinho
  - Em conjunto com o analista e/ou quem realizou a alteração conflitante com a minha.
- Após o merge, minha branch estará "up to date" e futuramente eu terei menos problema para fazer Pull Requests.
- Tenho alterações locais: ao tentar dar pull, sou forçado a dar commit (se tenho certeza de que já terminei) ou jogar códigos p/ stash (caso haja dúvida de ter concluído).

## 5. Fluxo de Ações: Atualização de Branch

Checkout "long-living" -> git pull -> Checkout "short-lived" -> git merge "long-living" -> (git push ou Conflitos -> Soluções de conflitos -> git push).
