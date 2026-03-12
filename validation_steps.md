I want you to create a Markdown file with QA validation steps for this story.

  Story / business context:
  <PASTE THE USER STORY OR SUMMARY>

  Acceptance criteria:
  <PASTE THE ACCEPTANCE CRITERIA>

  Implementation context:
  <DESCRIBE WHAT CHANGED>
  <BACKEND | FRONTEND | FULL STACK>
  <OPTIONAL: KEY FILES, ENDPOINTS, TABLES, FEATURE FLAGS, LOG EVENTS, QUEUES, INTEGRATIONS>

  Validation context:
  - QA can use: logs, database, Swagger, and the application UI when applicable
  - Environment: <DEV | QA | STAGING | OTHER>
  - Scope: <happy path only | happy path + edge cases | full regression-sensitive validation>

  Please generate a `.md` file containing validation steps that a QA analyst can execute without prior implementation knowledge.

  Requirements for the Markdown:
  1. Start with a short summary of what is being validated.
  2. Include prerequisites:
     - required data/setup
     - required users/roles/permissions
     - feature flags or configs, if applicable
  3. Include validation steps in execution order.
  4. For each step, include:
     - action to perform
     - expected result
     - where to validate it:
       - UI
       - API/Swagger
       - logs
       - database
  5. If applicable, include:
     - request payload examples
     - endpoints to call
     - database tables/fields to inspect
     - log messages or events to look for
  6. Include negative scenarios and edge cases when relevant.
  7. Include regression-sensitive checks if the change may affect existing behavior.
  8. If the change is frontend-related, include user navigation steps in the app.
  9. If the change is backend-related, include API, log, and database verification steps as applicable.
  10. End with a short section called `Notes / Risks` listing any important caveats, assumptions, or environment limitations.

  Output requirements:
  - Create the content in clean Markdown
  - Make the steps objective and testable
  - Do not be generic; tailor the instructions to the story and changed behavior
  - If important information is missing, state what is missing before generating the final file
