# GitHub Workflows

A collection of reusable GitHub Actions workflows for common development tasks.

## Available Workflows

### 📦 Pnpm Publish

**File:** `.github/workflows/pnpm-publish.yml`

Automates the publishing of npm packages using pnpm. Handles dependency updates, version incrementation, building, and publishing to npm.

### 📚 Deploy TypeDoc

**File:** `.github/workflows/deploy-typedoc.yml`

Generates TypeDoc documentation and deploys it to GitHub Pages. Configurable source paths, output directories, and TypeDoc options.

### 🔄 Subtree Sync

**File:** `.github/workflows/subtree-sync.yml`

Synchronizes a subtree/subfolder from a monorepo to a standalone repository using git subtree.

## Usage

These workflows are designed to be called from other repositories using the `workflow_call` trigger. Reference them in your repository's workflows to use these reusable actions.
