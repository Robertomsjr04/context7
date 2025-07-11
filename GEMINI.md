# Gemini Customization

This file helps Gemini understand our project's specific needs and conventions. By providing instructions here, we can guide its behavior for more accurate and efficient assistance.

## Project Overview

*   **Purpose:** A server for the Model Context Protocol (MCP), likely for a project named Context7.
*   **Tech Stack:** Node.js, TypeScript, and the Model Context Protocol SDK.
*   **Key Conventions:** [Mention any important coding styles, naming conventions, or architectural patterns.]

## Gemini's Role

*   **Tone:** Sempre responda em Português do Brasil (PT-BR).
*   **Tasks:** [Outline the primary tasks you expect Gemini to help with (e.g., "writing tests," "refactoring code," "generating documentation").]

## Instructions and Guidelines

*   **Testing:** The `test` script in `package.json` currently returns an error. You'll need to configure it properly before I can run tests.
*   **Linting/Formatting:** `npm run lint` to lint and `npm run format` to format the code.
*   **Dependencies:** [Explain how to add or manage dependencies (e.g., "Use `npm install` for new packages.").]
*   **Commit Messages:** [Describe the preferred format for commit messages (e.g., "Follow the Conventional Commits specification.").]
*   **File Structure:** [Briefly explain the layout of important directories.]

## Examples

*   **Good Interaction:**
    *   **User:** "Add a new component called 'UserProfile'."
    *   **Gemini:** [Creates the component file, a basic test, and a Storybook story, following all project conventions.]

*   **Bad Interaction:**
    *   **User:** "Fix the login bug."
    *   **Gemini:** [Makes a change without running tests, breaking the build.]
