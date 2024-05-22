# Flatten Codebase

## Overview

**Flatten Codebase** is a utility tool designed to simplify the process of preparing a codebase for analysis or processing by Language Models (LMs). It achieves this by flattening the entire codebase into a single Markdown (.md) file, making it easier for the developer to provide the codebase to the LM for various tasks such as code analysis, generation, or other natural language processing (NLP) activities.

## Table of Contents

- [Purpose](#purpose)
- [Features](#features)
- [Suggested system instructions](#suggested-system-instructions)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [Contributing](#contributing)

## Purpose

The primary goal of this tool is to streamline the workflow involved in providing a codebase to a LM for various tasks such as code analysis, generation, or other natural language processing (NLP) activities. By converting the codebase into a flat structure within a Markdown document, it allows developers to easily provide the codebase to the LM without the need for complex file handling or processing.

## Suggested system instructions
The file `system_instructions.txt` located on the project repository contains a suggestion of system instructions to be provided to the language model when using the codebase.md file generated by this tool. The argument `--system_instructions` can also be used to display these instructions in the terminal. Feel free to modify them to better fit your needs.

## Features

- **Directory Structure Representation**: Generates a structured representation of each specified folder's contents, including all nested directories and files.
- **File Content Extraction**: Extracts and includes the content of each file within the specified folders, facilitating direct analysis or processing by LMs.
- **Output in Markdown Format**: Outputs the flattened codebase in a Markdown file, ensuring compatibility with a wide range of tools and platforms that support Markdown.

## Getting Started

### Prerequisites

Ensure you have Python installed on your system. This tool requires Python 3.x.

### Installation

Install the CLI tool with pip:
  
```bash
pip install flatten-codebase
```

### Usage

Run the CLI with the `--folders` argument followed by the paths to the base folders you wish to process. For example:
```bash
flatten-codebase --folders /path/to/folder1 /path/to/folder2
```

This will create a `codebase.md` file in the current directory containing the flattened structure and the content of the specified folders.

## Contributing

Contributions to improve the tool's functionality, performance, or documentation are welcome. Please feel free to submit pull requests or issues through the GitHub repository.