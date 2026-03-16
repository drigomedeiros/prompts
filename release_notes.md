# Release Notes Prompt Template

We are preparing a production deployment for the service `<SERVICE_NAME>`.

## Deployment Context

- Audience: `<Business|Tech Manager>`
- Environment: `<PROD|STAGE>`
- Current tag: `<CURRENT_PROD_TAG>`
- Target deployment tag: `<TARGET_TAG>`
- Repository path: `<REPO_PATH>`
- Output file: `<OUTPUT_FILE>`
- Exclude non-prod-only changes? `<YES|NO>`

## Task

Create a production release notes document describing the changes between `<CURRENT_PROD_TAG>` and `<TARGET_TAG>`.

## Instructions

- Use git history and diff data from the repository at `<REPO_PATH>` as the source of truth.
- Compare only the changes introduced between `<CURRENT_PROD_TAG>` and `<TARGET_TAG>`.
- Write in a business analyst tone: clear, concise, and understandable by non-engineers.
- Focus on business impact, user-visible behavior, operational impact, and important internal changes that may affect production stability.
- Do not include low-value implementation details unless they materially affect production behavior or deployment risk.
- If there are changes that apply only to non-production environments and do not affect production behavior, exclude them.
- Include a deployment risk assessment on a scale from 1 to 5, where:
  - `1` = very low risk
  - `2` = low risk
  - `3` = moderate risk
  - `4` = high risk
  - `5` = very high risk
- The risk assessment must reflect service functionality and deployment stability, with a short explanation.
- Save the final document to `<OUTPUT_FILE>`.

## Output Format

1. Title
2. Deployment summary
3. Main changes included in this release
4. Business impact
5. Risks and points of attention
6. Risk assessment: `<RISK_SCORE>/5`
7. Short rollback considerations

## Notes

If the git history is not sufficient to confidently describe a change in business terms, infer carefully from commit messages and changed files, and say so conservatively.
