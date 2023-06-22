# Aula 12 - Resolvendo Conflitos

Nesta aula, exploramos o processo de resolução de conflitos ao trabalhar com repositórios Git. Aqui está um resumo dos passos realizados:

1. Simulação de conflito:
   - Alteramos o arquivo `index.html` no repositório remoto e nas mesmas linhas no arquivo `index.html` no repositório local.
   - O arquivo `index.html` estava na branch "novo-fix" no repositório local, enquanto no repositório remoto estava na branch principal.

2. Push para o repositório remoto:
   - Utilizamos o comando `git push --set-upstream origin novo-fiz` para enviar as alterações para o repositório remoto.
   - No entanto, digitamos o nome errado da branch, o correto seria "novo-fix".

3. Criação da pull request:
   - No GitHub, clicamos em "Compare & pull request" para criar a pull request.
   - Recebemos uma mensagem informando que não era possível mesclar automaticamente devido a conflitos.

4. Identificação dos conflitos:
   - Ao criar a pull request, foi identificado o problema de conflitos que precisavam ser resolvidos no arquivo `index.html`.

5. Resolução dos conflitos no GitHub:
   - Utilizamos a opção "Resolver conflitos" para visualizar onde os conflitos estavam ocorrendo no arquivo.
   - O GitHub forneceu um editor para resolver os conflitos diretamente na plataforma, mas não foi possível resolver completamente dessa maneira.

6. Visualização dos conflitos no VS Code:
   - No VS Code, alternamos para a branch "main" usando o comando `git checkout main`.
   - Atualizamos nossa branch local com as alterações remotas usando o comando `git pull`.

7. Tentativa de merge e identificação do conflito:
   - Tentamos realizar um merge, mas o Git identificou o conflito no arquivo `index.html`.

8. Resolução do conflito:
   - O professor demonstrou uma nova abordagem para resolver o conflito usando o Merger Editor.
   - Utilizamos o Merger Editor para corrigir manualmente todos os conflitos no arquivo `index.html`.

9. Envio das alterações para o repositório remoto:
   - Após resolver todos os conflitos, realizamos os procedimentos necessários para enviar as alterações para o repositório remoto.

10. Exclusão da branch:
    - Utilizamos o comando `git branch -d novo-fiz` para excluir a branch "novo-fiz" que não estava mais sendo usada.
