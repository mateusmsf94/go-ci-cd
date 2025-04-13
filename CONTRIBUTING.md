# Contributing to Go CI/CD Example

Thank you for your interest in contributing to this project! This document provides guidelines and steps for contributing.

## How to Contribute

1. Fork the repository
2. Create a new branch for your feature/fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Run the tests:
   ```bash
   go test -v ./...
   ```
5. Commit your changes:
   ```bash
   git commit -m "Description of your changes"
   ```
6. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
7. Create a Pull Request

## Code Style

- Follow the [Go Code Review Comments](https://github.com/golang/go/wiki/CodeReviewComments)
- Use `go fmt` to format your code
- Write tests for new features
- Keep commits focused and atomic

## Pull Request Process

1. Ensure your PR description clearly describes the problem and solution
2. Update the README.md if necessary
3. The PR must pass all GitHub Actions workflows
4. A maintainer will review your PR and may request changes

## Development Setup

1. Install Go 1.21 or later
2. Clone the repository:
   ```bash
   git clone https://github.com/mateusmsf94/go-ci-cd.git
   ```
3. Install dependencies:
   ```bash
   go mod download
   ```

## Questions?

Feel free to open an issue if you have any questions about contributing! 