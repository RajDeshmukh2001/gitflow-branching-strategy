# Git Flow Branching Strategy

This repository demonstrates the **Git Flow** branching strategy.

## About the Project
This is a simple static Library Dashboard built using:
- HTML
- CSS

---

## Branching Model

Git Flow uses **multiple long-lived branches** with clear responsibilities.

### Main Branches
- **main**
  - Contains production-ready code
  - Always stable and deployable

- **develop**
  - Integration branch for all completed features
  - Represents the latest development state

### Supporting Branches
- **feature/***
  - Used for developing new features
  - Created from `develop`
  - Merged back into `develop`

- **release/***
  - Used for preparing a production release
  - Created from `develop`
  - Merged into both `main` and `develop`

- **hotfix/***
  - Used for critical production fixes
  - Created from `main`
  - Merged into both `main` and `develop`