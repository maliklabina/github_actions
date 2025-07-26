# GitHub Actions Workflows

This repository contains a collection of GitHub Actions workflows designed to automate various tasks such as deployment, pull request handling, and workflow dependencies.


## 🚀 Workflows Overview

- **`auto_release.yml`**  
  Automates the release process when new changes are pushed to the main branch.

- **`cherry_pick.yml`**  
  Automatically cherry-picks changes from one branch to another based on custom logic.

- **`deploy.yml`**  
  Handles deployment to the target environment (e.g., production, staging).

- **`pull_request.yml`**  
  Runs checks and actions on pull request events (e.g., linting, testing).

- **`work_on_label.yml`**  
  Triggers actions when a specific label is applied to an issue or PR.

- **`workflow_dependency.yml`**  
  Manages dependencies between multiple workflows.

## 🧩 How to Use

These workflows are triggered automatically by GitHub events (e.g., `push`, `pull_request`, or `label`). To customize them for your project:

1. Clone this repo or copy individual workflow files.
2. Modify the `.yml` files as needed.
3. Push to your own repo with `.github/workflows` structure.

## 🛠 Requirements

- GitHub repository with Actions enabled.
- Permissions to create and run workflows.




