# Go CI/CD Example

A simple Go project demonstrating GitHub Actions workflow for continuous integration.

## Workflow Status

![CI](https://github.com/mateusmsf94/go-ci-cd/actions/workflows/go.yml/badge.svg)

## Project Structure

```
.
├── .github/workflows/go.yml  # GitHub Actions workflow
├── main.go                   # Main Go application
└── go.mod                    # Go module file
```

## Features

- Simple "Hello, World!" Go application
- GitHub Actions workflow for CI
- Automated testing and building
- Go module support

## Getting Started

1. Clone the repository
2. Run the application:
   ```bash
   go run main.go
   ```

## Workflow Details

The GitHub Actions workflow:
- Runs on push to main branch
- Runs on pull requests to main branch
- Can be triggered manually
- Sets up Go environment
- Builds and tests the project 