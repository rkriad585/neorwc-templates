# Plan: Internal Architecture Guide

**Goal:** Explain the code structure for future contributors.

**Required Files:**
1.  `docs/developer/architecture.md`: High-level system design.
2.  `docs/developer/modules.md`: Breakdown of `src/core` files.

**Instructions:**
- Analyze `src/core/scanner.js`: Explain how it ignores files and counts tokens.
- Analyze `src/core/ai.js`: Explain how it talks to Ollama and handles 400 errors.
- Analyze `src/core/writer.js`: Explain the `<<<FILENAME>>>` parsing logic.
- Analyze `src/core/config.js`: Explain the Global Path logic.
