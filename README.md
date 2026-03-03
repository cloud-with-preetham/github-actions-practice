# GitHub Actions Practice

A repository for learning and practicing GitHub Actions workflows and continuous integration concepts.

## Overview

This project contains example GitHub Actions workflows that demonstrate core CI/CD automation patterns. It serves as a practical learning resource for understanding how to configure and execute automated workflows in GitHub repositories.

## Project Structure

```
.github/
  workflows/
    hello.yml          # Basic workflow demonstrating workflow syntax and built-in variables
```

## Workflows

### Hello Workflow

**File:** `.github/workflows/hello.yml`

**Trigger:** Pushes to the `main` branch

**Features:**

- Checkout repository code
- Execute multiple shell commands
- Access and display GitHub Actions context variables
- Demonstrate environment variable usage
- Access runner information

**Steps:**

1. Checks out the repository code
2. Prints a greeting message
3. Displays the current date and time
4. Lists files in the working directory
5. Outputs all environment variables
6. Shows the current branch name
7. Displays the runner's operating system

## Usage

To use this repository:

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd github-actions-practice
   ```

2. Push changes to the `main` branch to trigger the workflow:

   ```bash
   git push origin main
   ```

3. Monitor workflow execution:
   - Navigate to the **Actions** tab in the GitHub repository
   - Select the workflow run to view logs and outputs

## Learning Resources

This project is designed to help you understand:

- Workflow syntax and structure
- Job and step configuration
- Built-in GitHub Actions context variables
- Environment variable access
- Runner specifications
- Basic shell command execution in workflows

## Requirements

- A GitHub account with repository access
- Git installed locally
- Understanding of basic YAML syntax

## Tips for Expansion

Consider extending this project to practice:

- Multiple jobs and job dependencies
- Matrix builds and strategy conditions
- Artifact creation and uploads
- Secret management and environment variables
- Custom actions and reusable workflows
- Conditional step execution
- Scheduled workflow triggers

## References

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Workflow Syntax for GitHub Actions](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [GitHub Actions Contexts](https://docs.github.com/en/actions/learn-github-actions/contexts)

## License

This project is provided as-is for educational purposes.
