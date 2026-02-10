# neorwc-templates

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![Node.js](https://img.shields.io/badge/Node.js-%3E%3D14-brightgreen)](https://nodejs.org/)  
[![CI](https://img.shields.io/github/actions/workflow/status/your-repo/neorwc-templates/ci.yml?branch=main)](https://github.com/your-repo/neorwc-templates/actions)

## Why neorwc‑templates?

`neorwc-templates` powers **Neorwc**, a local‑LLM‑driven documentation generator.  
- **Privacy‑first:** All processing stays on your machine—no data leaves the host.  
- **Speed & Security:** Leverages fast, offline LLMs (Llama 3, Mistral, etc.) without network latency.  
- **Flexibility:** Plug‑in any LLM backend, customize plans & skills, and share templates via GitHub.

## Key Features

- **Local LLM support** – works with Ollama, Llama 3, Mistral, and other self‑hosted models.  
- **Dynamic context‑window detection** – automatically adapts to the model’s token limits.  
- **Global Plans & Skills system** – store reusable documentation strategies under `~/.neorwc`.  
- **GitHub Template Store integration** – fetch ready‑made templates with `--install`.  
- **CLI‑first workflow** – generate docs directly from the terminal, scriptable for CI pipelines.

## Quick Start

```bash
# Install the CLI globally
npm install -g neorwc

# Initialise the configuration in your project
neorwc --init

# Generate documentation for the current repository
neorwc
```

## Configuration

Neorwc reads a `neorwc.md` file at the project root (or `~/.neorwc/neorwc.md` for global defaults).  
Define custom plans, override skill parameters, or set environment variables to tailor the output to your workflow.

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.

*written by Neorwc*