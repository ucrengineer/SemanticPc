# SemanticPC

SemanticPC is a versatile personal assistant application designed to help users perform various tasks on their PC through a command-line interface (CLI). This application leverages the power of .NET and the `System.CommandLine` library to provide a robust and extensible platform for automating everyday tasks.

## Features

- Perform Google searches directly from the CLI
- Extensible framework to add more personal assistant capabilities
- Simple and intuitive command structure

## Installation

To install SemanticPC, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/semanticpc.git
    cd semanticpc
    ```

2. Build the project using .NET SDK:
    ```sh
    dotnet build
    ```

## Usage

SemanticPC provides a command-line interface for interacting with the application. Below are the commands currently supported:

### Google Search

Perform a Google search from the CLI.

```sh
SemanticPC search "this is a test"
