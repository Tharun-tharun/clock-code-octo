## Explore

This project was developed collaboratively, resulting in a Rust implementation designed to faithfully reproduce the intended behavior.

Implementation [`src-rust-octo/`](https://github.com/Tharun-tharun/clock-code-octo/tree/main/src-rust-octo)- A separate AI agent built from the specification alone, without referencing the original TypeScript. The result is idiomatic Rust that reproduces the behavior, not the original implementation.

## How Did This Even Happen?

Developers often minify code before releasing it to make files smaller and harder to read. 
To debug this, they use source maps that map the compressed code back to the original.

These source maps are meant to stay internal but in this case, one was accidentally exposed. Lovely!

[![Claude Code source files exposed in npm package](https://raw.githubusercontent.com/kuberwastaken/claude-code/main/public/claude-files.png)](https://raw.githubusercontent.com/kuberwastaken/claude-code/main/public/claude-files.png)

---

## Update in-progress

Apologies for the limited README at the moment.
I’ll be updating it soon with more complete information about on the structure files.

# NOTICE

This repository does not hold a copy of the proprietary Claude Code typescript source code.
This is a clean Rust reimplementation of Claude Code's behavior.
