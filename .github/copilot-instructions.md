<!-- kumiq-instructions -->
## KumiQ Standards

Before starting any task, call the `get_standards` MCP tool with the inferred task_types.
Infer task_types from the request using these keywords:
- **feature**: add / new / implement / create / build / introduce
- **bug-fix**: fix / bug / broken / crash / incorrect / regression
- **refactor**: refactor / cleanup / restructure / simplify / rename
- **public-api**: API / endpoint / interface / contract / schema / export / CLI
- **config**: config / CI / CD / build / deployment / environment
- **migration**: migration / database / schema / backfill / alter
- **dependency**: dependency / package / upgrade / install / npm / yarn
- **docs**: docs / documentation / README / guide / changelog
- **architecture**: architecture / design / system / service / boundary

Use multiple types when the request spans categories. Call with no task_types when uncertain.
Follow returned standards and workflow guidance before writing any code.
<!-- /kumiq-instructions -->
