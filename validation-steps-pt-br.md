Quero que você crie um arquivo Markdown com os passos de validação de QA para esta story.

  Story / contexto de negócio:
  <COLE A USER STORY OU UM RESUMO>

  Critérios de aceitação:
  <COLE OS CRITÉRIOS DE ACEITAÇÃO>

  Contexto da implementação:
  <DESCREVA O QUE FOI ALTERADO>
  <BACKEND | FRONTEND | FULL STACK>
  <OPCIONAL: ARQUIVOS-CHAVE, ENDPOINTS, TABELAS, FEATURE FLAGS, EVENTOS DE LOG, FILAS, INTEGRAÇÕES>

  Contexto de validação:
  - O QA pode usar: logs, banco de dados, Swagger e a interface da aplicação, quando aplicável
  - Ambiente: <DEV | QA | STAGING | OUTRO>
  - Escopo: <apenas fluxo principal | fluxo principal + casos de borda | validação completa com foco em regressão>

  Por favor, gere um arquivo `.md` contendo passos de validação que um analista de QA consiga executar sem conhecimento prévio da implementação.

  Requisitos do Markdown:
  1. Comece com um breve resumo do que está sendo validado.
  2. Inclua os pré-requisitos:
     - dados ou setup necessário
     - usuários, perfis ou permissões necessárias
     - feature flags ou configurações, se aplicável
  3. Inclua os passos de validação em ordem de execução.
  4. Para cada passo, informe:
     - a ação a ser executada
     - o resultado esperado
     - onde validar:
       - UI
       - API/Swagger
       - logs
       - banco de dados
  5. Quando aplicável, inclua:
     - exemplos de payloads de requisição
     - endpoints a serem chamados
     - tabelas/campos do banco a serem verificados
     - mensagens de log ou eventos que devem ser observados
  6. Inclua cenários negativos e casos de borda, quando fizer sentido.
  7. Inclua verificações de regressão se a mudança puder impactar comportamentos existentes.
  8. Se a mudança envolver frontend, inclua os passos de navegação na aplicação.
  9. Se a mudança envolver backend, inclua validações por API, logs e banco, conforme aplicável.
  10. Finalize com uma seção chamada `Notas / Riscos`, listando pontos de atenção, premissas ou limitações do ambiente.

  Requisitos de saída:
  - Crie o conteúdo em Markdown limpo
  - Faça com que os passos sejam objetivos e testáveis
  - Não seja genérico; adapte as instruções à story e ao comportamento alterado
  - Se faltar alguma informação importante, diga exatamente o que está faltando antes de gerar o arquivo final
