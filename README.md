# Fix Editor Context Menu for Visual Studio Code

[![logo](./icon.png?raw=true)](https://github.com/hmir7/fix-editor-context-menu-vscode)

[![License](https://img.shields.io/github/license/hmir7/fix-editor-context-menu-vscode?logo=github)](http://www.gnu.org/licenses/gpl-3.0.en.html)

## Overview

This VS Code extension adds frequently used commands to the **top** of the editor context menu, making them easily accessible with a right-click.

### Features

The extension adds the following commands to the editor context menu (in order):

- **Cut** - Cut selected text to clipboard
- **Copy** - Copy selected text to clipboard
- **Paste** - Paste text from clipboard
- **Toggle Line Comment** - Add/remove line comment
- **Toggle Block Comment** - Add/remove block comment

These commands are placed at the very top of the context menu for quick access, improving your workflow efficiency.

## How It Works

This extension uses VS Code's `contributes.menus` API to place existing built-in commands at the top of the editor context menu with negative group ordering values. It doesn't add any custom logic - it simply makes the existing VS Code commands more accessible.

## Installation

### Manual Installation

1. Clone this repository or download it as a ZIP file
2. Open VS Code
3. Go to Extensions (Ctrl+Shift+X)
4. Click the "..." menu and select "Install from VSIX..."
5. Select the `fix-editor-context-menu-vscode` folder or build a VSIX package using `vsce package`

## Requirements

- Visual Studio Code version 1.60.0 or higher

## License

This extension is licensed under the [GNU General Public License v3.0](LICENSE).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Issues

If you encounter any issues or have feature requests, please file them on the [GitHub Issues page](https://github.com/hmir7/fix-editor-context-menu-vscode/issues).
