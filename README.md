# Common Gateway Components

This repository serves as a common components submodule for the new_gateway project, containing shared functionality for authentication, logging, and other common utilities.

## Structure

```
.
├── auth/           # Authentication related components
├── logging/        # Logging functionality
└── common/         # Shared utilities and components
```

## Usage

This repository is designed to be used as a git submodule. To include it in your project:

```bash
git submodule add [repository-url] common
git submodule update --init --recursive
```

## Dependencies

This module requires Python >=3.11.6 and uses Poetry for dependency management. See `pyproject.toml` for full dependency list.

## Development

1. Clone the repository
2. Install dependencies:
   ```bash
   poetry install
   ```
3. Run tests:
   ```bash
   poetry run pytest
   ```

## CI/CD

Continuous Integration is handled through GitHub Actions. See `.github/workflows/cicd.yml` for the complete pipeline configuration.

## License

See the LICENSE file for details.
