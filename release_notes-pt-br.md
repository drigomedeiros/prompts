# Template de Prompt para Release Notes

Estamos preparando um deploy em produção para o serviço `<SERVICE_NAME>`.

## Contexto do Deploy

- Público-alvo: `<Business|Tech Manager>`
- Ambiente: `<PROD|STAGE>`
- Tag atual: `<CURRENT_PROD_TAG>`
- Tag de destino do deploy: `<TARGET_TAG>`
- Caminho do repositório: `<REPO_PATH>`
- Arquivo de saída: `<OUTPUT_FILE>`
- Excluir mudanças exclusivas de ambientes não produtivos? `<YES|NO>`

## Tarefa

Criar um documento de release notes de produção descrevendo as mudanças entre `<CURRENT_PROD_TAG>` e `<TARGET_TAG>`.

## Instruções

- Use o histórico git e os diffs do repositório em `<REPO_PATH>` como fonte da verdade.
- Compare apenas as mudanças introduzidas entre `<CURRENT_PROD_TAG>` e `<TARGET_TAG>`.
- Escreva em um tom de analista de negócios: claro, conciso e compreensível para pessoas não engenheiras.
- Foque em impacto de negócio, comportamento visível ao usuário, impacto operacional e mudanças internas importantes que possam afetar a estabilidade em produção.
- Não inclua detalhes de implementação de baixo valor, a menos que eles afetem materialmente o comportamento em produção ou o risco do deploy.
- Se existirem mudanças que se aplicam apenas a ambientes não produtivos e não afetam o comportamento em produção, exclua essas mudanças.
- Inclua uma avaliação de risco do deploy em uma escala de 1 a 5, onde:
  - `1` = risco muito baixo
  - `2` = risco baixo
  - `3` = risco moderado
  - `4` = risco alto
  - `5` = risco muito alto
- A avaliação de risco deve refletir o funcionamento do serviço e a estabilidade do deploy, com uma explicação curta.
- Salve o documento final em `<OUTPUT_FILE>`.

## Formato da Saída

1. Título
2. Resumo do deploy
3. Principais mudanças incluídas nesta release
4. Impacto no negócio
5. Riscos e pontos de atenção
6. Avaliação de risco: `<RISK_SCORE>/5`
7. Considerações curtas sobre rollback

## Observações

Se o histórico git não for suficiente para descrever com segurança uma mudança em termos de negócio, infira com cuidado a partir das mensagens de commit e dos arquivos alterados, e sinalize isso de forma conservadora.
