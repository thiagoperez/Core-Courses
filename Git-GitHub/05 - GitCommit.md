# Aula 5 - Git Commit

Nesta aula, aprendemos sobre as melhores práticas relacionadas ao Git Commit. Veja abaixo os principais pontos abordados:

## 1. Adicione apenas as mudanças "certas"

- Evite fazer um único commit com todo o código escrito.
- Busque commitar apenas as alterações relacionadas a um "pequeno módulo".
- Quanto mais organizado e específico for o commit, melhor para todos.

## 2. Controlando o que será, ou não, commitado

- Utilize o comando `git diff` para visualizar as alterações feitas nos arquivos.
- Utilize o comando `git status` para verificar as alterações prontas para serem commitadas.
- Utilize o comando `git add` para adicionar as alterações desejadas ao commit.
- Revise o `git status` novamente para ter certeza das alterações a serem incluídas no commit.

## 3. Mensagens de commit

- O título da mensagem deve ser o mais conciso possível. Se tiver dificuldades para escrever um título curto, é sinal de que o commit pode estar muito grande.
- O corpo da mensagem deve conter uma explicação detalhada, incluindo a diferença entre o estado anterior e o atual, a razão para a mudança e informações extras relevantes.
- Utilize o comando `git commit -m "mensagem"` para adicionar uma mensagem ao commit.

## 4. .gitignore

- Utilize o arquivo `.gitignore` para listar os arquivos e artefatos que não devem ser commitados.
- Isso evita que arquivos desnecessários ou sensíveis sejam incluídos no repositório.

## 5. .env (dotenv)

- Utilize a biblioteca ou módulo .env em projetos JavaScript para ocultar informações importantes, como chaves de API ou senhas.
- O .env permite armazenar essas informações em um arquivo separado, não rastreado pelo Git.

## 6. Fluxo de ações para executar um commit

1. Escreva o código correspondente à funcionalidade ou correção desejada.
2. Utilize `git add` para adicionar as alterações ao stage.
3. Verifique o status das alterações com `git status`.
4. Utilize `git commit` para realizar o commit das alterações adicionadas ao stage, adicionando uma mensagem significativa.
5. Utilize `git push` para enviar as alterações para o repositório remoto.
6. Se trabalhando em equipe, crie um pull request para revisão antes de mesclar as alterações com a branch principal.

É importante seguir essas práticas para garantir um histórico de commits organizado e consistente.