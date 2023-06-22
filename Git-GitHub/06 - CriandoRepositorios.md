# Aula 6 - Hands-on: Criando e trabalhando com Git nos repositórios

Nesta aula prática, exploramos a criação e o trabalho com o Git em repositórios. Veja abaixo os passos e conceitos abordados:

1. Criação de um Repositório Simples no GitHub:
   - Acesse o GitHub e crie um novo repositório.

2. Criando uma pasta e abrindo no VS Code:
   - No seu ambiente de trabalho, crie uma nova pasta para o projeto.
   - Abra o VS Code e selecione a opção de abrir uma pasta existente.
   - Selecione a pasta criada anteriormente.

3. Executando o comando `git init`:
   - No terminal integrado do VS Code, execute o comando `git init`.
   - Esse comando inicializa o repositório Git na pasta selecionada.

4. Conceito de funcionamento do Git no VS Code:
   - O professor explicou como o Git funciona no ambiente do VS Code.

5. Criação do arquivo README.md:
   - No VS Code, crie um novo arquivo chamado README.md.
   - O arquivo README.md é uma boa prática para fornecer informações sobre o projeto.

6. Adicionando arquivos em um commit:
   - Aprendemos a usar o comando `git add <nomeArquivo.ext>` para adicionar arquivos em um commit.

7. Realizando o primeiro commit:
   - Executamos o comando `git commit -m "msg"` para fazer o primeiro commit das alterações.
   - Utilizamos uma mensagem descritiva para o commit.

8. Verificando o status das alterações:
   - Utilizamos o comando `git status` para conferir se há algo a ser commitado.

9. Visualizando o histórico de commits:
   - Utilizamos o comando `git log` para ver a lista do histórico de commits realizados.

10. Atualizando o projeto:
    - Ao fazer alterações no arquivo README.md, precisamos executar novamente o comando `git add README.md` para atualizar o projeto.

11. Realizando novos commits:
    - Executamos `git commit` para criar um novo commit com as alterações.
    - Utilizamos uma mensagem descritiva para cada commit.

12. Mantendo os commits apenas localmente:
    - As publicações estão apenas na máquina local até o momento.

13. Criando um arquivo index.html:
    - Criamos um arquivo index.html como exemplo adicional.

14. Atualizando todos os arquivos:
    - Utilizamos o comando `git add .` para atualizar todos os arquivos do projeto.

15. Criando mais um commit:
    - Executamos o comando `git commit` para criar um novo commit com as alterações adicionadas.

16. Visualizando as alterações com `git diff`:
    - Utilizamos o comando `git diff` para ver todas as alterações realizadas.

17. Deletando um arquivo:
    - Deletamos o arquivo index.html.

18. Atualizando novamente:
    - Executamos `git add .` para atualizar o repositório com a alteração.

19. Separando os commits:
    - Aprendemos a separar os commits, enviando apenas a alteração que deletou o arquivo index.html.
    - Para isso, executamos o comando `git restore --staged README.md` para remover o arquivo README.md do stage.

20. Realizando um novo commit:
    - Executamos o comando `git commit -m "Mensagem do commit"` para criar um novo commit com as alterações desejadas.

21. Mudando o nome da branch principal:
    - Utilizamos o comando `git branch -M main` para alterar o nome da branch principal para "main".

22. Conectando ao repositório remoto:
    - Informamos ao Git que iremos conectar ao repositório remoto usando o comando `git remote add origin URLDoRepositório`.
    
23. Verificando a URL do repositório remoto:
    - Descobrimos o endereço do repositório remoto utilizando o comando `git remote get-url origin`.

24. Enviando os commits para o GitHub:
    - O primeiro push precisa ser realizado com o comando `git push -u origin main` para conectar ao repositório remoto na branch principal.

25. Fazendo login no GitHub:
    - Se for a primeira vez realizando o push, será solicitado que faça login no GitHub.

26. Realizando o commit no GitHub:
    - O commit foi enviado para o GitHub com sucesso.

27. Atualizando o arquivo README.md localmente:
    - Realizamos as devidas atualizações no arquivo README.md no repositório local.
    - Em seguida, fizemos o commit e enviamos as alterações para o GitHub usando o comando `git push`.