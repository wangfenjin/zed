# Zed-Spacemacs Keymap

This project adapts Spacemacs key bindings for use in the Zed editor, bringing the ergonomic and mnemonic space-based key combinations to Zed's modern editing environment.

## Features

- Space-prefixed key bindings similar to Spacemacs
- Vim mode compatibility
- Git integration with magit-inspired commands
- Terminal, project management, and navigation shortcuts

## Installation

1. Clone this repository to `~/.config/` or
2. Copy the `keymap.json` and `settings.json` files to your Zed configuration directory:
   - macOS: `~/.config/zed/`
   - Linux: `~/.config/zed/`
   - Windows: `%APPDATA%\Zed\`

## Key Bindings

### Core

- `space f e d` - Open keymap file
- `space '` - Toggle terminal
- `space tab` - Alternate file

### Files & Buffers

- `space b b` - File finder
- `space b s` - New file
- `space 1-9` - Switch to tab 1-9

### Git

- `space g s` - Toggle Git panel
- `space g b` - Git blame

### Navigation & Search

- `space j i` - Toggle outline
- `space /` - New search
- `space *` - Search current word

### Projects

- `space p p` - Open recent project
- `space p t` - Toggle project panel
- `space p f` - File finder

### Other

- `space c l` - Toggle comments
- `space a i` - Toggle AI agent

## Git Panel Bindings

- `tab` - Show diff
- `c c` - Commit
- `b b` - Checkout branch
- `b c` - Create branch, actually in Zed they are kind of the same
- `P u` - Push
- `F u` - Pull
- `s` - Toggle staged
- `S` - Stage all

## Configuration

This project includes:
- `keymap.json` - All Spacemacs-like key bindings
- `settings.json` - Base configuration with vim mode enabled
- `tasks.json` - Optional tasks for git and search operations, not used for now

## Feedback

Feel free to use and provide feedback on this configuration. Contributions are welcome!
