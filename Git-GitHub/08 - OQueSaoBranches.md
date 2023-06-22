# Aula 8: Branches: Linhas / Trilhas de Publicação de Código

Na oitava aula, o professor Pietro Martins de Oliveira abordou o tema "Branches: Linhas / Trilhas de Publicação de Código" no Git. Veja os principais pontos discutidos:

1. Modelos de Controle de Versão:
   - As Branches podem ser divididas entre Branches de State, Release e Features.
   - Branches diferentes têm propósitos distintos.
   - Existem diferentes modelos/fluxos, dependendo da empresa/projeto.

2. Branches de State, Release e Features:
   - Branches "long-running": main e develop:
     - Refletem os estágios do ciclo de desenvolvimento.
     - Geralmente, não se faz commits diretamente, mas sim Pull Requests e Merges.
   - Branches "short-lived": features e fixes:
     - Focadas em novas funcionalidades, correções, refatoramentos, provas de conceito, etc.
     - Geralmente são deletadas após a integração.

3. Branch única:
   - Poucas ou uma única branch, com commits relativamente pequenos.
   - O modelo mais simples, geralmente utilizado quando apenas uma pessoa está trabalhando no código.
   - Muito comum em projetos pessoais.
   - O professor demonstrou uma única trilha de publicações.

4. GitHub Flow - Modelo Enxuto:
   - Apenas uma branch "long-running".
   - Sem restrições para branches de fix, features, etc.
   - O professor demonstrou a criação de uma branch feature (short-lived) e, ao concluí-la, foi feito um merge na branch principal com as novas atualizações. O mesmo exemplo foi mostrado para a branch bug fix (short-lived).

5. Gitflow - Modelo mais estruturado, com mais regras:
   - Duas ou mais branches "long-running".
   - Sem restrições para branches de fix, features, etc.
   - O professor deu o exemplo de uma branch develop servindo como intermediária para a branch principal.

6. Fluxo de ações: git checkout
   - Branch "long-living" -> git checkout -> Branch "short-lived" -> add + commit + push -> Pull Request "long-living".
