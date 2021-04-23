ADR Action
---

Action to generate [Architecture Decision Records](https://adr.github.io/) Table of Contents and ADR Graph dependency into a README.md in the ADR dir.

To Setup
---

```yaml
- uses: jules2689/adr-action@main
  with:
    adr-dir: '' # Optional. Directory in which ADRs are located. Defaults to contents of .adr-dir
    adr-tool-repo: 'https://github.com/npryce/adr-tools.git' # Optional. ADR Tool Repo location 
    adr-tool-version: '3.0.0' # Optional. Version of the Tools to use.
    github-token: '' # Optional. Token with which to commit
    generate-toc-branches: [main, master] # Optional: JSON Array of Branch names as a string. specify which branches we should generate TOC on. Defaults to main/master. 
```
