We want to merge the current branch into `main`.

  Please review the current branch against the diff target and business context below.

  Diff target:
  - Compare the current branch against `main`
  - Review scope: <changed files only | changed files plus integration impact>

  User story / business context:
  <PASTE THE USER STORY>

  Acceptance criteria:
  <PASTE THE ACCEPTANCE CRITERIA, IF AVAILABLE>

  Review objectives:
  1. Verify whether the implementation is adherent to the user story and acceptance criteria.
  2. Identify gaps, incorrect assumptions, or missing scenarios relative to the expected business behavior.
  3. Assess whether the changes may unexpectedly break existing behavior or introduce regressions.
  4. Evaluate test coverage for the scenarios added or changed:
     - Are the main business flows covered?
     - Are edge cases and regression risks covered?
     - Are any important tests missing?
  5. Evaluate code quality:
     - Clean code principles
     - Readability and maintainability
     - Dead code or unnecessary complexity
     - Compliance with the project’s current patterns and code style
     - Compliance with the project’s current patterns, code style, and approved language/runtime version conventions (especially the project’s adopted LTS version)
     - Avoid recommending changes that depend on language features or idioms outside the project’s supported versio
     - Sound engineering practices

  Review output format:
  - List findings first, ordered by severity.
  - For each finding, include:
    - what is wrong
    - why it matters
    - where it is
    - what should be changed
  - Then state:
    - whether the branch is acceptable to merge
    - residual risks
    - missing tests, if any

  If important review context is missing, tell me exactly what is missing before concluding.
