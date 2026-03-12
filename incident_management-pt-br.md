Quero que você crie um arquivo Markdown com a análise de um incidente com base no codebase atual.

  Relato do incidente:
  <COLE EXATAMENTE O QUE O USUÁRIO INFORMOU>

  Comportamento esperado:
  <DESCREVA O QUE DEVERIA TER ACONTECIDO>

  Ambiente:
  <PROD | STAGING | QA | DEV | OUTRO>
  <OPCIONAL: TENANT / LOJA / REGIÃO / PLATAFORMA / VERSÃO DO APP / NAVEGADOR / DISPOSITIVO>

  Contexto adicional:
  <COLE QUALQUER CONTEXTO EXTRA, SE HOUVER>

  Evidências:
  - Screenshots / imagens: <ANEXE OU DESCREVA, SE HOUVER>
  - Logs: <COLE, SE HOUVER>
  - Mensagens de erro: <COLE, SE HOUVER>
  - IDs / timestamps / usuários afetados / registros afetados: <COLE, SE HOUVER>

  Objetivo da análise:
  Analise o codebase e avalie se o comportamento relatado é tecnicamente possível com base na implementação atual e no contexto fornecido.

  Instruções:
  1. Analise o relato do incidente e correlacione-o com o codebase atual.
  2. Compare o comportamento relatado com o comportamento esperado.
  3. Determine se o comportamento relatado:
     - é claramente suportado pela implementação atual
     - é plausível sob condições específicas
     - não é suportado pelo código como está implementado
  4. Identifique os caminhos de código, condições, validações, integrações ou casos de borda mais prováveis relacionados ao incidente.
  5. Se houver screenshots, logs ou outras evidências, correlacione-os com o código e explique se reforçam ou contradizem a hipótese.
  6. Aponte premissas, dúvidas ou informações ausentes que limitem a confiança da análise.
  7. Quando fizer sentido, identifique:
     - causa raiz provável
     - possíveis condições de disparo
     - componentes ou fluxos impactados
     - se isso parece bug, mau uso, problema de dados, problema de ambiente, problema de configuração ou problema de integração
  8. Se aplicável, sugira próximos passos concretos de investigação, como:
     - logs a inspecionar
     - tabelas/campos a verificar
     - APIs/endpoints a testar
     - feature flags/configurações a confirmar
     - fluxos de UI para reproduzir
  9. Gere um arquivo `.md` com a análise.

  Estrutura do Markdown:
  - Resumo do incidente
  - Comportamento esperado
  - Comportamento relatado
  - Ambiente
  - Evidências fornecidas
  - Análise técnica
  - Caminhos de código relevantes
  - Hipóteses / possíveis causas
  - Nível de confiança
  - Lacunas / informações faltantes
  - Próximos passos recomendados
  - Conclusão

  Requisitos de saída:
  - Baseie a análise no codebase real, e não apenas em especulação
  - Deixe explícito quando algo for inferência e não fato confirmado
  - Mantenha a escrita concisa, objetiva e técnica
  - Se faltar informação importante, diga exatamente o que está faltando antes de concluir
