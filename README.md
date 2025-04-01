# dot-files

A repository containing configuration files and guides for Motia framework development with Cursor AI.

## Overview

This repository provides:

- Cursor AI rules for Motia framework development
- Claude AI guide for generating Motia workflows
- Configuration files for optimal development experience

## Contents

- `.cursor/rules/`: Cursor AI rules for working with Motia framework components:
  - `api-steps.mdc`: API endpoint creation and configuration
  - `architecture.mdc`: Overall Motia framework architecture
  - `cron-steps.mdc`: Scheduled task configuration
  - `event-steps.mdc`: Event handling and emission
  - `state-management.mdc`: Managing state between steps
  - `steps.mdc`: Core concepts and step creation
  - `testing.mdc`: Unit and flow testing guidelines
  - `typescript.mdc`: TypeScript types for Motia
  - `ui-steps.mdc`: Workbench visualization components
- `CLAUDE.md`: Comprehensive guide for Claude AI to generate Motia workflows

## Getting Started

1. Clone this repository
```bash
git clone https://github.com/motia/dot-files.git
```

2. Copy the configuration files to your Motia project
```bash
cp -r .cursor your-motia-project/
```

3. Use Cursor AI with the provided rules to enhance your Motia development experience

## Features

- **Motia Rules**: Guidelines for Cursor AI to understand Motia framework concepts including:
  - Core components (steps, flows, events)
  - Step types (API, Event, Cron, NOOP)
  - State management between steps
  - UI components and styling
  - Testing workflows and best practices

- **Claude AI Guide**: Comprehensive documentation on how to use Claude for generating Motia workflows with:
  - Step templates for TypeScript, JavaScript, Python, and Ruby
  - Configuration patterns
  - State management conventions
  - Example prompts and implementations

## Usage

When using Cursor AI with these configurations, you'll get enhanced assistance for:

- Creating properly structured steps
- Following Motia naming conventions
- Implementing correct event patterns
- Building flows that adhere to best practices
- Generating consistent UI components

## License

MIT
