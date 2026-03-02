# GitHub Actions Course !!!

A hands-on learning repository with practical examples and notes for mastering GitHub Actions.
Preparing for a production migration.

## 📚 Workflows

This repository contains example workflows demonstrating key GitHub Actions concepts:

### 01 - Building Blocks
**File:** `.github/workflows/01-building-blocks.yaml`
- Basic workflow structure
- Multiple jobs and steps
- Manual workflow triggering with `workflow_dispatch`

**Concepts covered:**
- Job definitions and execution
- Step commands with `run`
- Exit codes and step success

### 02 - Workflow Events
**File:** `.github/workflows/02-workflow-events.yaml`
- Different workflow triggers
- Event context variables

**Concepts covered:**
- `pull_request` trigger
- `workflow_dispatch` for manual runs
- Accessing event information with `${{ github.event_name }}`

### 03 - Workflow Runners
**File:** `.github/workflows/03-workflow-runners.yaml`
- Cross-platform workflow execution
- Runner environment variables

**Concepts covered:**
- Ubuntu, Windows, and macOS runners
- Platform-specific configurations
- Accessing runner information with `${{ runner.os }}` and `$RUNNER_OS`

## 🚀 Usage

Workflows can be triggered:
- Manually via the **Actions** tab → Select workflow → **Run workflow**
- Automatically based on configured triggers (push, pull_request, etc.)

## 📖 Learning Path

1. Start with `01-building-blocks.yaml` to understand workflow basics
2. Explore `02-workflow-events.yaml` to learn about triggers
3. Review `03-workflow-runners.yaml` for cross-platform execution
