<!--
SPDX-FileCopyrightText: 2024 Ali Sajid Imami

SPDX-License-Identifier: MIT
-->

# .github Repository

This repository contains GitHub-specific configurations and workflows for the project. Below is a detailed explanation of the files and their roles within this repository.

## Files and Directories

### `CONTRIBUTING.md`

This document provides guidelines for contributing to the project. It includes information on the code of conduct, how to report issues, and the process for submitting pull requests.

### 3. `ISSUE_TEMPLATE/`

This directory contains templates for creating issues. These templates help standardize the information provided when reporting bugs, requesting features, or asking questions. Common files include:

- `bug_report.md`: Template for reporting bugs.
- `feature_request.md`: Template for requesting new features.
- `custom.md`: Template for other types of issues.

### 4. `PULL_REQUEST_TEMPLATE.md`

This file provides a template for pull requests. It helps contributors include all necessary information when submitting a pull request, such as a description of changes, related issues, and testing instructions.

### 5. `./github/workflows/`

This directory contains GitHub Actions workflows. These workflows automate various tasks such as running tests, building the project, and deploying code.

### 6. `./github/workflows-templates/`

This directory contains the templates for some useful workflows that can be used downstream in the rest of the organization repositories. This allows for centralizing specific common workflows while allowing all the other repositories to benefit from it.

### 7. `./github/actions/`

This directory contains commonly used actions and actions that have shared logic for other workflows and workflow templates.

### 8. `FUNDING.yml`

This file contains default funding avenues for this organization. This way, only files with differing information need to be added to repositories.

### 7. `SECURITY.md`

This document outlines the security policies for the project. It includes information on how to report security vulnerabilities and the process for handling them.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
