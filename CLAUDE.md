# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Buildathon competition project focused on rapidly prototyping innovative AI solutions. The repository is set up for Python development.

## Development Setup

Since this is a new project, common Python development commands will depend on the specific framework and dependencies chosen:

### Python Project Commands (to be updated as project develops)
- **Virtual Environment**: `python -m venv venv` then `source venv/bin/activate` (macOS/Linux)
- **Install Dependencies**: Will use `pip install -r requirements.txt` once requirements.txt is created
- **Running Tests**: Will depend on test framework chosen (pytest, unittest, etc.)
- **Linting**: Consider using `ruff` or `flake8` for Python linting
- **Type Checking**: Consider using `mypy` for static type checking

## Project Structure

Currently minimal - the project is in initial setup phase. As the codebase grows, this section should be updated with:
- Main application entry points
- Core modules and their responsibilities
- Key architectural decisions
- External dependencies and integrations

## MCP Servers

### GitHub MCP Server
The GitHub MCP server is configured for this project, enabling direct GitHub operations:
- Create issues, pull requests, and manage repositories
- Access GitHub API functionality through Claude Code
- Requires GITHUB_PERSONAL_ACCESS_TOKEN environment variable to be set

## Notes

- The .gitignore is configured for Python projects including common virtual environments, caches, and IDE files
- The project targets rapid prototyping for a one-day AI solution competition
- GitHub MCP server is installed and configured for GitHub operations