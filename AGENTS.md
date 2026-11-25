## Commit guidelines

Every commit must be a conventional commit. Please follow the following guidelines below when commiting changes to this repository:

- Use the present tense
- Use the imperative mood in the subject line
- Limit the subject line to 50 characters or less
- Capitalize the subject line
- Do not end the subject line with a period
- use Feat: for new features
- use Fix: for bug fixes

## Security guidelines
- never commit secrets or sensitive information to the repository (e.g., passwords, API keys, private keys, etc.)
- SQL queries should be parameterized to prevent SQL injection attacks
- XSS vulnerabilities should be mitigated by properly escaping user input and using secure coding practices