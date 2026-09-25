# Contributing Guidelines

Thank you for considering contributing to this project! Please take a moment to review the following guidelines to make the contribution process smooth and efficient.

## Table of Contents

- [Code Style](#code-style)
- [Commit Message Format](#commit-message-format)
- [Branching Strategy](#branching-strategy)
- [Submitting Pull Requests](#submitting-pull-requests)
- [License](#license)

## Code Style

- **Language**: Follow the idiomatic style of the primary language used in the repository (e.g., PEP 8 for Python, ESLint/Prettier for JavaScript/TypeScript).
- **Formatting**: Run the project's formatter before committing (e.g., `black .` for Python, `npm run format` for JS/TS).
- **Linting**: Ensure the code passes all linting checks (`flake8`, `eslint`, etc.).
- **Naming Conventions**:
  - Variables and functions: `snake_case` (Python) or `camelCase` (JS/TS).
  - Classes: `PascalCase`.
  - Constants: `UPPER_SNAKE_CASE`.
- **Documentation**: Add docstrings/comments where appropriate. Public APIs should have clear docstrings.
- **Tests**: Include unit/integration tests for new features or bug fixes. Aim for high coverage.

## Commit Message Format

Follow the conventional commits specification:

```
<type>(<scope>): <subject>

<body>

<footer>
```

- **type**: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, etc.
- **scope** (optional): the component or module affected.
- **subject**: short description (max 50 characters, no period).
- **body** (optional): detailed explanation, motivation, and any background information.
- **footer** (optional): references to issues (e.g., `Closes #123`).

Example:
```
feat(auth): add OAuth2 login flow

Implemented OAuth2 using the provider's SDK. Updated documentation and added unit tests.

Closes #45
```

## Branching Strategy

- **main**: Protected branch; always reflects production-ready code.
- **develop** (if present): Integration branch for upcoming releases.
- **Feature branches**: `feature/<short-description>`
- **Bugfix branches**: `bugfix/<short-description>`
- **Hotfix branches**: `hotfix/<short-description>`

### Workflow
1. **Sync**: Ensure your local `main` (or `develop`) is up‑to‑date.
2. **Create a branch**: `git checkout -b feature/awesome-feature`.
3. **Commit**: Follow the commit message format.
4. **Push**: `git push origin feature/awesome-feature`.
5. **Open a PR**: Target `main` (or `develop`).

## Submitting Pull Requests

1. **Open PR**: From your feature/bugfix/hotfix branch to the `main` branch.
2. **Title**: Use a clear, concise title (e.g., `feat: add user profile page`).
3. **Description**:
   - Brief overview of what the PR does.
   - Link to related issue(s) (`Closes #XYZ`).
   - Any additional context or screenshots.
4. **Review**: Request reviewers and address feedback.
5. **CI**: Ensure all checks pass (tests, linting, build).
6. **Merge**: Once approved, squash‑merge or rebase‑merge according to project policy.

## License

By contributing, you agree that your contributions will be licensed under the project's LICENSE.
