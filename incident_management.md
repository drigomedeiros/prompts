 I am working on an incident and I want you to create a Markdown file with the incident assessment.

  Incident report:
  <PASTE THE USER’S DESCRIPTION EXACTLY AS RECEIVED>

  Additional context:
  <PASTE ANY EXTRA CONTEXT, IF AVAILABLE>

  Evidence:
  - Screenshots / images: <ATTACH OR DESCRIBE, IF AVAILABLE>
  - Logs: <PASTE, IF AVAILABLE>
  - Error messages: <PASTE, IF AVAILABLE>
  - IDs / timestamps / affected users / affected records: <PASTE, IF AVAILABLE>

  Assessment goal:
  Please inspect the codebase and assess whether it is technically possible for the reported behavior to happen based on the current implementation.

  Instructions:
  1. Analyze the incident report and correlate it with the current codebase.
  2. Determine whether the reported behavior is:
     - clearly supported by the current code
     - plausible under specific conditions
     - not supported by the current code as implemented
  3. Identify the most likely code paths, conditions, validations, integrations, or edge cases related to the incident.
  4. If screenshots, logs, or other evidence were provided, correlate them with the code and explain whether they reinforce or contradict the hypothesis.
  5. Call out any assumptions, unknowns, or missing information that limit confidence in the assessment.
  6. If relevant, identify:
     - likely root cause
     - possible triggering conditions
     - impacted components or flows
     - whether this looks like a bug, misuse, data issue, environment issue, or integration issue
  7. If applicable, suggest concrete next investigation steps, such as:
     - logs to inspect
     - tables/fields to verify
     - APIs/endpoints to test
     - feature flags/configuration to confirm
  8. Generate a `.md` file with the assessment.

  Markdown structure:
  - Incident summary
  - Reported behavior
  - Evidence provided
  - Technical assessment
  - Relevant code paths
  - Hypotheses / possible causes
  - Confidence level
  - Gaps / missing information
  - Recommended next steps
  - Conclusion

  Output requirements:
  - Base the assessment on the actual codebase, not speculation alone
  - Be explicit when something is an inference rather than a confirmed fact
  - Keep the writing concise, objective, and technical
  - If important information is missing, say exactly what is missing before concluding
