# Plan: README Overhaul

## Objective
Generate a high-quality, engaging `README.md` for Neorwc that clearly communicates its value, features, and quick start instructions, encouraging developers to install and use it immediately.

---

## Required File
- `README.md` (root directory)

---

## Content Structure

### 1. Title & Badges
- Project name: **Neorwc**
- Badges: License, Node.js version, optional CI/CD status

### 2. The "Why"
- Brief explanation emphasizing:
  - Uses local LLMs (e.g., Ollama, Llama3, Mistral)
  - Code never leaves the machine
  - Focus on secure, fast, and private documentation generation

### 3. Key Features
- Local LLM support (Llama3, Mistral, etc.)
- Dynamic context window detection
- Global Plans & Skills system (`~/.neorwc`)
- GitHub Template Store integration (`--install`)

### 4. Quick Start
- `npm install -g neorwc`
- `neorwc --init`
- `neorwc`

### 5. Configuration
- Brief explanation of `neorwc.md` and how it customizes plans or workflows

---

## Documentation Standards
- Keep language clear, concise, and persuasive
- Highlight unique selling points and practical benefits
- Include short, actionable code examples for installation and usage
- Base all content on actual features and workflows of Neorwc

---

## Analysis Method
1. Extract core Neorwc features from code and existing docs
2. Generate badges and relevant project metadata
3. Summarize the tool’s unique value proposition
4. Include quick start commands and configuration notes
5. Output as a single professional `README.md`