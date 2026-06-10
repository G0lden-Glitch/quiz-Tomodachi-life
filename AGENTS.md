# Agent Instructions

This workspace is a small static site for a Tomodachi Life quiz. Keep changes focused on the existing HTML and CSS unless the user asks for more.

## Project Shape

- Main UI lives in [index.html](index.html) and [style.css](style.css).
- [read.md](read.md) is reference material for learning notes; do not treat it as app code.
- There is no build system or package manager in the workspace.

## Working Rules

- Prefer small, local edits over broad rewrites.
- Preserve the existing French content and the quiz structure unless the request says otherwise.
- Keep the page simple, readable, and responsive.

## Terminal

- The environment is Windows, so use PowerShell-friendly commands when you need the terminal.
- Avoid bash-only syntax and assumptions about Linux tooling.
- For quick checks, use the terminal to inspect files or confirm the workspace layout; do not expect a build step.

## Validation

- Validate UI changes by opening or reloading [index.html](index.html) in the browser.
- If you need to inspect text quickly, prefer direct file reads over adding new tooling.