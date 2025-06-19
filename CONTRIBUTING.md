# Contributing to Utility AI MuleSoft API

We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## We Develop with GitHub

We use GitHub to host code, to track issues and feature requests, as well as accept pull requests.

## We Use [GitHub Flow](https://guides.github.com/introduction/flow/index.html)

Pull requests are the best way to propose changes to the codebase. We actively welcome your pull requests:

1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code follows the existing code style.
6. Issue that pull request!

## Any contributions you make will be under the MIT Software License

In short, when you submit code changes, your submissions are understood to be under the same [MIT License](LICENSE) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report bugs using GitHub's [issues](https://github.com/yourusername/utility-ai-mulesoft-api/issues)

We use GitHub issues to track public bugs. Report a bug by [opening a new issue](https://github.com/yourusername/utility-ai-mulesoft-api/issues/new); it's that easy!

## Write bug reports with detail, background, and sample code

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

## Development Process

### Prerequisites

- MuleSoft Anypoint Studio 7.x or higher
- Maven 3.6+
- Java 8 or 11
- Access to Anypoint Platform

### Setting Up Your Development Environment

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/utility-ai-mulesoft-api.git
   cd utility-ai-mulesoft-api
   ```

2. Import the project into Anypoint Studio
   - File → Import → Anypoint Studio Project from File System
   - Select the project directory

3. Configure your Anypoint Platform credentials
   - Update `~/.m2/settings.xml` with your credentials

### Code Style Guidelines

Please follow the conventions outlined in:
- [config/naming-conventions.yaml](config/naming-conventions.yaml)
- [config/error-handling-standards.yaml](config/error-handling-standards.yaml)
- [config/versioning-rules.yaml](config/versioning-rules.yaml)

Key points:
- Use kebab-case for URI paths
- Use camelCase for JSON properties
- Follow RESTful conventions
- Include proper error handling with standardized error responses

### Testing

1. Write MUnit tests for all new functionality
2. Place tests in the appropriate `/tests` subdirectory
3. Ensure all tests pass before submitting PR:
   ```bash
   mvn clean test
   ```

### API Documentation

- Update OpenAPI specifications in `/api-specs` when modifying APIs
- Follow OpenAPI 3.0.1 standards
- Include examples for request/response payloads
- Document all error scenarios

### Commit Messages

- Use clear and meaningful commit messages
- Start with a verb in present tense: "Add", "Fix", "Update", "Remove"
- Reference issues and pull requests when applicable
- Example: "Add circuit breaker pattern to Grid Coordination API (#123)"

## Pull Request Process

1. Update the README.md with details of changes if applicable
2. Update the CHANGELOG.md following [Keep a Changelog](https://keepachangelog.com/) format
3. Increase version numbers following our [versioning rules](config/versioning-rules.yaml)
4. The PR will be merged once you have the sign-off of at least one maintainer

## Community

- Join our discussions in [GitHub Discussions](https://github.com/yourusername/utility-ai-mulesoft-api/discussions)
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

Thank you for contributing to the Utility AI MuleSoft API project!