# Pip-Audit

[Pip-Audit](https://github.com/pypa/pip-audit) is a tool to audit Python environments and dependencies for known vulnerabilities. It works by scanning your Python packages and comparing them against the Python Packaging Advisory Database.

## Workflow Integration

This repository includes a workflow configuration for Pip-Audit that can be integrated into your CI/CD pipeline.

### Contents

- **`workflow.yaml`**: A sample GitHub Actions workflow to run Pip-Audit on each pull request or push.
- **`.pre-commit-config.yaml`**: A sample configuration file for pre-commit hooks to run Pip-Audit locally before code is committed.

## Setup

1. **GitHub Actions Integration**:
   To integrate Pip-Audit into your CI/CD pipeline with GitHub Actions, copy the contents of the `workflow.yaml` file into your repository under `.github/workflows/`. This workflow will automatically run Pip-Audit on your dependencies whenever you push code or create a pull request.

2. **pre-commit Hooks**:
   To integrate Pip-Audit into your pre-commit hooks, copy the contents of the `.pre-commit-config.yaml` file into your repository's `.pre-commit-config.yaml` file. This will ensure that Pip-Audit is run locally before code is committed. You may need to adjust the paths to your requirements files if they are located elsewhere. It is also recommended to ensure the [pre-commit](https://github.com/pre-commit/pre-commit) tool is installed and configured in your repository.


   ```bash
   pip install pre-commit
   pre-commit install
   ```
