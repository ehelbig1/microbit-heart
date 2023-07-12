## Git Configuration

This repository uses it's own git configuration to define a standard git commit message template and pre-commit hook. The template can be found in the .gitmessage file and all git hooks are defined in the hooks/ directory. To enable this configuration run:

```bash
git config --local include.path ../.gitconfig
```

## Install Binutils

Binutils provides lots of utilities for interacting with an executable.

```bash
cargo install cargo-binutils
```

## Flashing Program

Make sure you have __cargo-embed__ installed on your machine.

```bash
cargo install cargo-embed
```

To flash your program, make sure you have your Microbit connected to your computer and run:

```bash
cargo embed --target thumbv7em-none-eabihf
```

