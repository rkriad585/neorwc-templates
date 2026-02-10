# Plan: Standard README

## Objective
Generate a single, professional `README.md` in the project root that clearly communicates the project’s purpose, features, installation, usage, configuration, and license. Only a single README should be created; no other files.

---

## Required File
- `README.md` (root directory)

---

## Content Structure

### 1. Title & Description
- Clear project name
- One-line elevator pitch describing what the project does

### 2. Features
- Bullet points of the top 5 capabilities or technical highlights
- Focus on concrete, code-based features detectable from the project

### 3. Installation
- Provide the appropriate install command:
  - Node.js: `npm install <package>`
  - Python: `pip install <package>`
  - Rust: `cargo install <package>`
- Optional: any pre-requisites if required

### 4. Usage
- Short “Hello World” code snippet demonstrating core functionality
- Include minimal example showing how to run or import the project

### 5. Configuration
- Table of environment variables or CLI flags:
  | Name | Type | Default | Description |
- Include only variables detectable from the project

### 6. License
- Clearly state the license type
- Optional: link to LICENSE file if present

---

## Documentation Standards
- Keep language concise, professional, and actionable
- Base content strictly on the actual code and project metadata
- Include practical examples and tables where relevant
- Avoid creating additional files beyond `README.md`

---

## Analysis Method
1. Detect project type and dependencies (`package.json`, `requirements.txt`, `Cargo.toml`, etc.)
2. Extract top features, modules, or capabilities from the code
3. Generate installation command(s) and minimal usage example
4. Extract environment variables or CLI flags for configuration table
5. Output a single, fully structured `README.md` file