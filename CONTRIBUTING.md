# Contributing to CoordinateKit

Thank you for your interest in contributing to CoordinateKit! This document provides guidelines and instructions for contributing to repositories in the coordinatekit organization.

## Code of Conduct

This project adheres to a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to conduct@coordinatekit.org.

## How to Contribute

### Reporting Bugs

Before creating a bug report, please check existing issues to avoid duplicates. When creating a bug report, include:

- A clear, descriptive title
- Steps to reproduce the issue
- Expected behavior vs actual behavior
- Your environment (language/runtime version, OS, library version)
- Relevant logs or error messages
- A minimal code example that reproduces the issue

### Suggesting Enhancements

Enhancement suggestions are welcome! Please include:

- A clear, descriptive title
- A detailed description of the proposed enhancement
- The motivation and use case
- Examples of how the enhancement would be used

### Pull Requests

We use a fork and pull request workflow:

1. **Fork the repository** - Create your own fork of the project on GitHub

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
   cd REPO_NAME
   ```

3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
   Use descriptive branch names:
   - `feature/` for new features
   - `fix/` for bug fixes
   - `docs/` for documentation changes
   - `refactor/` for code refactoring

4. **Make your changes** - Write your code following our coding standards

5. **Write tests** - Add tests for any new functionality

6. **Run the test suite** - Refer to the repository's README for specific test commands

7. **Check code formatting** - Run any linting or formatting checks specified in the repository

8. **Commit your changes**
   ```bash
   git add .
   git commit -m "Brief description of changes"
   ```
   Write clear, concise commit messages that explain what and why.

9. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

10. **Open a Pull Request** - Go to the original repository and create a pull request from your fork

## Development Setup

Each repository has its own development requirements and build process. Please refer to the repository's README for:

- Prerequisites and dependencies
- Build instructions
- How to run tests
- Code coverage tools (if applicable)

## Coding Standards

### Code Style

Each repository may have its own style guide and formatting tools. Check the repository's README or configuration files for specific style requirements. When in doubt, follow the existing code style in the project.

### Testing

- Write unit tests for all new functionality
- Maintain or improve code coverage
- Use descriptive test method names that explain what is being tested
- Follow the Arrange-Act-Assert pattern

### Documentation

- Add documentation comments for all public APIs
- Keep documentation up to date with code changes
- Include usage examples in documentation where helpful

## Pull Request Guidelines

### Before Submitting

- [ ] Code compiles/builds without errors
- [ ] All tests pass
- [ ] Code is properly formatted (run any linting/formatting checks)
- [ ] New code has appropriate test coverage
- [ ] Documentation is updated if needed

### PR Description

Your pull request description should include:

- A summary of the changes
- The motivation for the changes
- Any breaking changes
- Related issue numbers (e.g., "Fixes #123")

### Review Process

1. A maintainer will review your PR
2. Address any requested changes
3. Once approved, a maintainer will merge your PR

## Questions?

If you have questions about contributing, feel free to:

- Open an issue in the relevant repository with the "question" label
- Reach out to the maintainers

Thank you for contributing to CoordinateKit!
