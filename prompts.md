I removed the skills in `_templates/skills` and moved them to their own repository. Make sure that there are no references in the code, the tests or in the docs that require the skills markdown files in `_templates/skills`.

If the codebase requires the skills, create an github issue.
If a test requires the skills, remove the test.
If documentation refers to a skill, refer to repo "https://github.com/agent-fox-dev/skills".

Use a workflow for the above task.