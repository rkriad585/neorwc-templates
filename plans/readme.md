# Plan: Single README Generation

## Objective
Generate a single `README.md` file that summarizes the project in a clear, concise, and professional way. Do not create any additional files.

---

## Required File
- `README.md` (root of the project)

---

## Content Structure

### 1. Header
- Project name
- Dynamic badges: License, Language, Version, CI/CD (if detectable)

### 2. Elevator Pitch
- One sentence clearly describing the purpose or functionality of the project

### 3. Features
- Bullet points summarizing key technical capabilities found in the code
- Include modules, functions, or workflows if identifiable

### 4. Installation
- Provide the appropriate install command:
  - `npm install <package>` for Node.js
  - `pip install <package>` for Python
  - `go get <package>` for Go

### 5. Usage Example
- Short code block demonstrating the most common or core usage pattern

### 6. License
- Footer stating the license type
- Optional: link to `LICENSE` file if present

---

## Documentation Standards
- Base content strictly on actual code and project structure
- Keep language concise and punchy
- If content exceeds 500 words, summarize without losing clarity
- Include practical examples and detect relevant badges automatically

---

## Analysis Method
1. Detect project type (`Node`, `Python`, `Go`, etc.)
2. Extract key features, modules, or functions from code
3. Generate installation command based on package type
4. Include short usage example demonstrating core functionality
5. Summarize license and add dynamic badges
6. Output as a single, professional `README.md`