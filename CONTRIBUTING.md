# Contributing

This repository is the profile and project index for `022UGDW213`. Changes should keep the page accurate, accessible, and easy to render on GitHub.

## Guidelines

- Keep project descriptions factual and link to the canonical repository or deployment.
- Prefer accessible alt text for images and avoid relying on color alone.
- Keep external badges and widgets limited to services that are stable and relevant.
- Do not commit credentials, API keys, private URLs, generated secrets, or personal data.
- Validate Markdown and inspect the rendered README before opening a pull request.

## Local validation

```bash
grep -nE '^#+ ' README.md
git diff --check
```

### Security

Report suspected vulnerabilities privately through GitHub rather than posting credentials or exploit details in a public issue.

