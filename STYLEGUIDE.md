# Style Guide for the Meal Planning App

This style guide aims to keep our codebase clean, consistent, and easy to read. By adhering to these guidelines, we ensure that our code is maintainable and understandable by everyone who works on it.

## Python Style Guide

### General Principles
- **Readability Counts**: Write code that's easy to read and understand.
- **Consistency**: Follow the conventions set in this document and existing code.
- **Self-Explanatory Code**: Aim for clarity in your code; comments should be used to explain why, not what.

### Formatting
- **Indentation**: Use 4 spaces per indentation level.
- **Line Length**: Keep lines to a maximum of 79 characters.
- **Imports**: Group imports as standard library, third-party, and local. Within each group, sort alphabetically.

### Naming Conventions
- **Variables**: Use `lower_case_with_underscores`.
- **Functions**: Use `lower_case_with_underscores`.
- **Classes**: Use `CapWords` convention.
- **Constants**: Use `UPPER_CASE_WITH_UNDERSCORES`.

### Comments
- Use comments sparingly and focus on writing self-documenting code.
- When necessary, comments should be clear and concise.
- Use docstrings for module, function, class, and method documentation.

## Django Best Practices

### Models
- Use clear, descriptive names for models and fields.
- Write docstrings for each model.
- Prefer explicit `ForeignKey` relationships over implicit.

### Views
- Keep business logic out of views; use services or utility functions instead.
- Use Class-Based Views when possible for consistency.

### Templates
- Keep logic minimal in templates. Focus on presentation.
- Use template inheritance efficiently.

## JavaScript/CSS (If applicable)

### General
- Follow consistent naming and formatting conventions.
- Prefer readability and maintainability over complex one-liner solutions.

### JavaScript
- Use `camelCase` for identifiers.
- Prefer ES6 syntax and features where appropriate.

### CSS
- Use BEM (Block Element Modifier) or similar methodologies for naming.
- Organize stylesheets logically and comment sections.

## Git Workflow

### Commits
- Write clear, concise commit messages.
- Each commit should represent a single logical change.
- Group related changes into a single commit.

### Branches
- Use descriptive names for branches: `feature/<feature-name>`, `bugfix/<bug-name>`.
- Keep branches up-to-date with the `main` branch.

## Testing

- Write tests for new features and bug fixes.
- Follow [pytest/Django testing framework] conventions.
- Aim for thorough coverage but prioritize key areas.

## Linters and Formatters

- Use [flake8/pylint/black] for Python.
- Configure linters/formatters according to the project's setup.

---

This style guide is a living document and may evolve as our project grows. Always keep an eye on updates and revisions. If in doubt, refer to the existing codebase as a reference for the style and format to use.
