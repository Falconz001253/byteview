# byteview

Fast line/byte counter written in Rust

Small but I use it weekly.

## Installation

```bash
cargo build --release
```

## What it does

- Reads stdin or multiple files
- Parallel over files with std threads
- Counts lines, words and bytes like wc
- Zero dependencies outside std

## Usage

```bash
./target/release/byteview src/*.rs
cat README.md | ./target/release/byteview
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   └── roadmap.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
└── Cargo.toml
```
