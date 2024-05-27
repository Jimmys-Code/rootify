# Rootify

[![PyPI version](https://badge.fury.io/py/rootify.svg)](https://badge.fury.io/py/rootify)

Rootify is a lightweight Python package that ensures your scripts always run from the project root, solving the common headache of relative imports and path issues.

## The Problem

### Path Issues in Python Projects

When working on a Python project, scripts often need to be executed from various directories. This leads to:

- **Inconsistent Imports**: Relative imports may fail because the script's location affects how modules are found.
- **Complex Path Management**: Developers need to adjust paths manually, complicating the codebase.
- **Testing Challenges**: Running tests from different locations can break imports, making testing cumbersome.

### Typical Scenario

Imagine a project where you have a script that relies on modules located in different directories. Running this script from various locations within your project often requires tweaking the import paths, making the code less portable and harder to maintain.

## The Solution

### How Rootify Works

Rootify simplifies your development workflow by automatically setting the working directory to the project root. This ensures consistent and reliable imports, regardless of where you run your scripts from within the project.

## Benefits

- **Simplified Imports**: No need for complex path adjustments; imports work as expected.
- **Consistent Environment**: Your scripts behave the same way regardless of their execution location.
- **Ease of Testing**: Run tests from any directory without worrying about broken imports.

## Installation

Install Rootify from PyPI:

```sh
pip install rootify

```
## How to use

simply put:
```python
import rootify
```



