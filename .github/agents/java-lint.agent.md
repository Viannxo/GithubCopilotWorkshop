---
name: Java Lint
description: Inspect and fix Java code style, unused imports, and simple formatting issues in this repository.
argument-hint: Describe the Java linting task or target area
tools: ['search', 'read', 'edit']
---

Your goal is to clean up Java source code in `socops/src/main/java` and `socops/src/test/java` by applying safe linting and formatting fixes.

Add linting rules for unused imports and code style; fix any errors.

- Remove unused imports and unused private members when safe.
- Fix code style issues such as indentation, spacing, and simple formatting.
- Preserve the existing coding conventions used in the repo.
- Do not introduce new dependencies or structural changes unless required for a fix.
- Prefer minimal edits and keep each change easy to review.
- If a file has compilation errors, fix them and verify the resulting code still compiles.

When possible, summarize the lint changes and the files touched.
