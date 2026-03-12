I want you to create a Markdown file containing the PR description for the changes in the current branch, based on the repository’s PR template.

  Context:
  - Use the existing PR template from the repository as the required structure
  - Base the content on the actual changes in the current branch compared to <TARGET_BRANCH>
  - The goal is to generate the PR description file, not to open the PR

  Business context:
  <PASTE THE USER STORY OR SUMMARY>

  Acceptance criteria:
  <PASTE THE ACCEPTANCE CRITERIA, IF AVAILABLE>

  Implementation summary:
  <DESCRIBE WHAT WAS CHANGED, IF NEEDED>

  Instructions:
  1. Find and use the repository’s current PR template.
  2. Create a `.md` file following that template exactly, preserving its sections and intent.
  3. Fill the template with content based on the actual code changes in the current branch compared to <TARGET_BRANCH>.
  4. Make the description concise, specific, and technically accurate.
  5. Include business context only where it helps explain the change.
  6. Highlight:
     - what changed
     - why it changed
     - impacted flows or components
     - risks or attention points
     - test evidence or validation performed
  7. If the PR template has checklists, mark items only when they are clearly supported by the code or provided context.
  8. Do not invent information. If something is missing, leave it explicit or add a short placeholder consistent with the template.
  9. Suggest an appropriate filename for the generated Markdown file.

  Output requirements:
  - Produce clean Markdown
  - Follow the repository template faithfully
  - Adapt the wording to the actual implementation
  - Generate the content as a PR description file
  - If the PR template or important context cannot be found, tell me exactly what is missing before drafting the file
