# Aula 15 - Git Revert & Git Reset - Revertendo / desfazendo alterações no código

1. Git Revert

    - Comando utilizado para desfazer mudanças em um repositório.
    - Cria-se um commit que inverte todas as alterações desejadas a partir de um commit desejado.
    - Mantém o histórico dos commits não mais usados evita a perda do histórico de trabalho.
    - `git revert`.

2. Git Reset

    - Desfaz as alterações salvas e coloca o repositório no estado em que se encontrava anteriormente.
    - Opções para o comando git reset:
        --soft`: reseta apenas o commit history.
        --mixed`: reseta o commit history e os arquivos staged.
        --hard`: reseta tudo -> commit history, arquivos staged e até arquivos salvos "not staged".

3. CUIDADO

- O git reset pode fazer você perder seu progresso.
- Faça backups manuais, para "evitar a fadiga"!
