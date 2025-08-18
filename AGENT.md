# AI Agent Instructions

This document provides a set of guidelines for any AI agent assisting with the development of this project.

## 1. Project Overview

*   **Project Name:** Strength & Conditioning AI Coach
*   **Objective:** [To be filled in: Briefly describe the main goal of the application.]

## 2. General Instructions

*   **Interaction Style:** Provide shell commands as text responses instead of executing them directly using tools. The user will execute them.
*   **Workflow:** Before starting any new development task, read this `AGENT.md` file to load the project's context and rules, and explicitly state that you are doing so.
*   **Proactiveness:** [To be filled in: e.g., "Proactively suggest improvements," "Ask for clarification before making significant changes."]
*   **File Handling:** Always confirm before deleting files or making widespread changes.

## 3. Technology Stack

*   **Frontend:** [To be filled in: e.g., "React (Next.js) with TypeScript"]
*   **Backend:** [To be filled in: e.g., "Python (FastAPI)"]
*   **Database:** [To be filled in: e.g., "PostgreSQL"]
*   **Styling:** [To be filled in: e.g., "Material-UI"]

## 4. Coding Style & Conventions

*   **Formatting:** [To be filled in: e.g., "Follow Prettier defaults," "Use 2 spaces for indentation."]
*   **Naming Conventions:** [To be filled in: e.g., "Use camelCase for variables and functions," "Component files should be PascalCase."]
*   **Comments:** [To be filled in: e.g., "Comment complex logic, but avoid commenting on obvious code."]
*   **Commit Messages:** All commit messages must follow the Conventional Commits specification with the following strict rules:
    *   **Format:** `TYPE(scope): Subject`
    *   **Header Length:** Must be under 80 characters.
    *   **Body Line Length:** Must be under 100 characters.
    *   **Type (Mandatory, UPPERCASE):** Must be one of the following:
        *   `BLD`: Updates to the build process/scripts and/or CD pipelines
        *   `TST`: Additions/updates to tests
        *   `ENH`: Enhancement of existing functionality
        *   `FEAT`: New functionality
        *   `BUG`: Bug fix
        *   `DOC`: Additions/updates to documentation
        *   `STY`: Style fixes that do not affect code meaning (white-space, PEP8, etc)
        *   `PERF`: Performance improvement
        *   `MAINT`: Maintenance commit (refactoring, typos, code cleanup)
        *   `REL`: Related to the release process
        *   `EXP`: Experiments and data analysis
        *   `DEV`: Development tool or utility
        *   `DEP`: Deprecate something, or remove a deprecated object
        *   `UI`: Change related to UI
        *   `CI`: Change to the CI pipeline (e.g. github actions)
        *   `DATA`: Addition of sample data
    *   **Scope (Mandatory):** A short noun identifying the area of the codebase (e.g., `api`, `auth`, `db`, `ui-kit`, `docs`).
    *   **Subject (Mandatory):** Must be in sentence-case and must NOT end with a period.

## 5. Architectural Patterns

*   **Frontend:** [To be filled in: e.g., "Use a component-based architecture," "Separate state management using Zustand/Redux."]
*   **Backend:** [To be filled in: e.g., "Use a service-repository pattern," "All endpoints should have OpenAPI schema definitions."]

## 6. Testing

*   **Frameworks:** [To be filled in: e.g., "Jest for unit tests, Cypress for E2E tests."]
*   **Test Command:** `[To be filled in: e.g., "npm test"]`
*   **Philosophy:** [To be filled in: e.g., "Aim for >80% code coverage," "Write tests for all new features."]

## 7. Common Commands

*   **Run Development Server:** `[To be filled in]`
*   **Run Linter:** `[To be filled in]`
*   **Build for Production:** `[To be filled in]`
