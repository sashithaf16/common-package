# README.md for common-package

# Common Package

The `common-package` is a collection of Go modules that provide various utilities and functionalities. Each sub-module is designed to be independent and can be versioned separately.

## Sub-modules

### Random Module

- **Path**: `random`
- **Description**: This module provides functionality to generate random UUIDs.
- **Usage**: Import the `random` package and use the `RandomNumber` function to get a new random UUID as a string.

### Other Module

- **Path**: `other-module`
- **Description**: This module contains additional functionalities that complement the `random` module.
- **Usage**: Import the `other-module` package to access its features.

## Installation

To use the `common-package`, you can import the desired sub-module in your Go project. Ensure that you have Go modules enabled.

## Versioning

Each sub-module maintains its own versioning through the `go.mod` file, allowing for independent updates and dependency management.

## Contribution

Contributions are welcome! Please feel free to submit a pull request or open an issue for any enhancements or bug fixes.