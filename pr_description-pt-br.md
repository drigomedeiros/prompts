Quero que você crie um arquivo Markdown contendo a descrição do PR para as mudanças da branch atual, com base no template de PR existente no repositório.

  Contexto:
  - Use o template de PR existente no repositório como estrutura obrigatória
  - Baseie o conteúdo nas mudanças reais da branch atual em comparação com <TARGET_BRANCH>
  - O objetivo é gerar o arquivo `.md` com a descrição do PR, e não abrir o PR

  Contexto de negócio:
  <COLE A USER STORY OU UM RESUMO>

  Critérios de aceitação:
  <COLE OS CRITÉRIOS DE ACEITAÇÃO, SE HOUVER>

  Resumo da implementação:
  <DESCREVA O QUE FOI ALTERADO, SE NECESSÁRIO>

  Instruções:
  1. Encontre e utilize o template de PR atual do repositório.
  2. Crie um arquivo `.md` seguindo exatamente esse template, preservando suas seções e intenção.
  3. Preencha o template com base nas mudanças reais do código da branch atual em comparação com <TARGET_BRANCH>.
  4. Escreva uma descrição concisa, específica e tecnicamente precisa.
  5. Inclua contexto de negócio apenas quando isso ajudar a explicar a mudança.
  6. Destaque:
     - o que mudou
     - por que mudou
     - fluxos ou componentes impactados
     - riscos ou pontos de atenção
     - evidências de teste ou validação realizadas
  7. Se o template de PR tiver checklists, marque itens apenas quando isso estiver claramente sustentado pelo código ou pelo contexto fornecido.
  8. Não invente informações. Se algo estiver faltando, deixe isso explícito ou use um placeholder curto compatível com o template.
  9. Sugira um nome apropriado para o arquivo Markdown gerado.

  Requisitos de saída:
  - Gere Markdown limpo
  - Siga fielmente o template do repositório
  - Adapte o texto à implementação real
  - Gere o conteúdo como um arquivo de descrição de PR
  - Se o template de PR ou algum contexto importante não puder ser encontrado, diga exatamente o que está faltando antes de gerar o arquivo
