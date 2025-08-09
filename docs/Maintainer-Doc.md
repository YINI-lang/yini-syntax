# Maintainer-Doc

## Packaging as VSCode Extension

The following is the process of packaging this project as a VSCode extension.

### 1. Install the Publishing Tool

If `vsce` is not yet installed, install by:
```bash
npm install -g vsce
```

### 2. Package the Extension

From the `yini-syntax` project root:
```bash
vsce package
```
This will create a file like `yini-syntax-1.0.0.vsix`.

## Install Local Extension

### 1. Install Extension Globally in VSCode:

Install the created file, in above steps, in VSCode:
```bash
code --install-extension yini-syntax-1.0.0.vsix
```
