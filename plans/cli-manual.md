# Plan: Cli User Manual

## Objective
Generate a comprehensive `docs/` folder documenting all features, usage patterns, and configuration options. Focus on actionable, step-by-step guides for end users.

---

## Required Files

### 1. docs/usage/installation.md
- Explain global vs local installation
- Include prerequisites and environment setup
- Provide copy-pasteable commands

### 2. docs/usage/commands.md
- Detailed table of all CLI flags (e.g., `-i`, `-t`, `-c`)
  | Flag | Type | Default | Description |
- Include examples of usage for each flag
- Base on actual code and CLI parsing

### 3. docs/features/templates.md
- Explain how to use the templates feature
- Provide examples of common templates
- Include instructions for fetching from GitHub (or other remote sources)

### 4. docs/features/customization.md
- Explain how to create or customize templates, plans, or workflows
- Include practical code blocks and configuration examples
- Describe file locations and naming conventions

---

## Documentation Standards
- Base content strictly on the actual project implementation
- Provide clear, copy-pasteable commands and code blocks
- Keep language concise and step-by-step
- Include examples for verification

---

## Analysis Method
1. Scan code for all CLI flags and default values
2. Inspect template and workflow logic to explain usage
3. Extract installation steps and prerequisites
4. Generate structured guides covering usage, commands, templates, and customization