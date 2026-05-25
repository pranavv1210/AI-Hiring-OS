```markdown
# AI-Hiring-OS Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns and conventions used in the AI-Hiring-OS JavaScript codebase. You'll learn about file naming, import/export styles, commit message habits, and how to write and run tests. This guide helps maintain consistency and efficiency when contributing to the repository.

## Coding Conventions

### File Naming
- Use **PascalCase** for all file names.
  - **Example:**  
    ```
    CandidateProfile.js
    InterviewScheduler.js
    ```

### Import Style
- Use **relative imports** for modules within the project.
  - **Example:**
    ```javascript
    import CandidateProfile from './CandidateProfile';
    import utils from '../utils/helpers';
    ```

### Export Style
- Use **default exports** for modules.
  - **Example:**
    ```javascript
    // CandidateProfile.js
    const CandidateProfile = () => { /* ... */ };
    export default CandidateProfile;
    ```

### Commit Messages
- Freeform style, no enforced prefixes.
- Average commit message length: ~30 characters.
  - **Example:**  
    ```
    Add candidate filtering logic
    Fix bug in interview scheduler
    ```

## Workflows

_No automated workflows detected in this repository._

## Testing Patterns

- **Test File Naming:**  
  Test files use the `*.test.*` pattern, typically colocated with the code they test.
  - **Example:**  
    ```
    CandidateProfile.test.js
    utils.test.js
    ```

- **Testing Framework:**  
  Not explicitly detected. Check the repository for a `package.json` or documentation to confirm the testing tool in use.

- **Test Example:**
    ```javascript
    // CandidateProfile.test.js
    import CandidateProfile from './CandidateProfile';

    test('renders candidate name', () => {
      // ...test implementation...
    });
    ```

## Commands

| Command    | Purpose                                |
|------------|----------------------------------------|
| /test      | Run all test files in the repository   |
| /lint      | Lint the codebase for style issues     |
| /format    | Format code according to conventions   |
| /commit    | Create a new commit with your changes  |

> _Note: Actual command implementation may depend on project scripts or tooling. Adjust as needed for your environment._
```