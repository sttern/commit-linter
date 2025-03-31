# commit-linter

Overview

Commit Linter is a GitHub Action that ensures all commit messages follow a structured format before they are merged into the main branch. By enforcing a consistent commit style, this tool improves readability, makes versioning easier, and keeps the project history clean.

Why Use This?

Ensures commit messages follow a standardized format (e.g., Conventional Commits).

Helps developers write meaningful commit messages.

Improves collaboration and project maintainability.

Automatically checks commits in pull requests.


Commit Message Format

This linter enforces the Conventional Commits standard:

<type>(<scope>): <description>

Allowed Types

feat: A new feature

fix: A bug fix

docs: Documentation updates

style: Code style changes (formatting, missing semicolons, etc.)

refactor: Code restructuring without behavior changes

test: Adding or modifying tests

chore: Maintenance tasks (dependencies, build process updates)


Examples of Correct Commits

✅ feat(auth): add OAuth login support

✅ fix(ui): resolve button alignment issue

✅ docs(readme): update installation steps

Examples of Incorrect Commits

❌ fixed bug in login (Missing type and scope)

❌ updated README (Doesn’t specify the change)
