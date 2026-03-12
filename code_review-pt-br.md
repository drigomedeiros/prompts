Revise a branch atual considerando o alvo do diff e o contexto de negócio abaixo.

  Alvo do diff:
  - Comparar a branch atual com a `main`
  - Escopo da revisão: <apenas arquivos alterados | arquivos alterados mais impacto de integração>

  User story / contexto de negócio:
  <COLE A USER STORY AQUI>
  

  Critérios de aceitação:
  <COLE OS CRITÉRIOS DE ACEITAÇÃO, SE HOUVER>

  Objetivos da revisão:
  1. Verificar se a implementação está aderente à user story e aos critérios de aceitação.
  2. Identificar lacunas, suposições incorretas ou cenários ausentes em relação ao comportamento de negócio esperado.
  3. Avaliar se as mudanças podem quebrar comportamentos existentes de forma inesperada ou introduzir regressões.
  4. Avaliar a cobertura de testes para os cenários adicionados ou alterados:
     - Os principais fluxos de negócio estão cobertos?
     - Casos de borda e riscos de regressão estão cobertos?
     - Há testes importantes faltando?
  5. Avaliar a qualidade do código:
     - Princípios de clean code
     - Legibilidade e manutenibilidade
     - Código morto ou complexidade desnecessária
     - Conformidade com os padrões atuais do projeto e com o estilo de código
     - Conformidade com os padrões atuais do projeto, estilo de código e convenções aprovadas de versão da linguagem/runtime, especialmente a versão LTS adotada pelo projeto
     - Evitar recomendar mudanças que dependam de recursos da linguagem ou de idiomatismos fora da versão suportada pelo projeto
     - Boas práticas de engenharia

  Formato da resposta:
  - Liste primeiro os achados, ordenados por severidade.
  - Para cada achado, informe:
    - o que está errado
    - por que isso importa
    - onde está o problema
    - o que deve ser alterado
  - Depois, informe:
    - se a branch está apta para merge
    - riscos residuais
    - testes faltantes, se houver

  Se faltar algum contexto importante para uma revisão confiável, diga exatamente o que está faltando antes de concluir.
