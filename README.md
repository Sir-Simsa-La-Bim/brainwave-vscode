# Brainwave for Visual Studio Code

Editing support for the **Brainwave** algorithm description language and `.brnw` files.

## Features

- Syntax highlighting for Brainwave declarations, sections, layouts, literals, directives, and Brainfuck commands
- Comment support for `//`, `#`, and `/* ... */`
- Bracket matching and automatic closing
- Basic indentation and folding
- Snippets for functions, blocks, `goto`, `hint`, preserved blocks, and literals

## Scope

This is Phase 1 editing support. It does not parse Brainwave semantically, compile to Brainfuck, or report language diagnostics.

## Try it locally

1. Open this folder in Visual Studio Code.
2. Press `F5` to launch an Extension Development Host.
3. Open `examples/sample.brnw` in the new window.

Alternatively, package the extension with `npx @vscode/vsce package` and install the resulting VSIX with **Extensions: Install from VSIX...**.

## File extension

Brainwave source files use `.brnw`.
