# Custom Key Bindings for Visual Studio Code (Mac)

This repository contains a set of custom key bindings for Visual Studio Code, specifically tailored for Mac users. These key bindings are designed to override and enhance the default shortcuts, making your coding experience on macOS even more productive and efficient. However, most of these bindings are likely to work on Windows and Linux as well.

## Installation

To use these custom key bindings, follow these steps:

1. Clone this repository to your local machine.
2. In Visual Studio Code, open the command palette by pressing `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS).
3. Search for "Preferences: Open Keyboard Shortcuts (JSON)" and select it.
4. Copy and paste the contents of the `keybindings.json` file from this repository into the JSON file that opens in Visual Studio Code.
5. Save the file.

## Custom Key Bindings

Here is a list of the custom key bindings included in this repository:

### PANEL

- Toggle terminal: `Cmd+J`
- Move to GitHub Copilot chat tab: `Cmd+L` (when panel is focused)
- Focus on text input when the panel is focused: `Cmd+;` (when panel is focused)

### SEARCH

- Open find: `Ctrl+/` (when editor is focused, open, or text input is focused)

### TEXT MOVEMENT

- Delete all characters to the left: `Cmd+Backspace` (when text input is focused and not in readonly mode)
- Undo action: `Ctrl+U` (when text input is focused and not in readonly mode)
- Redo action: `Ctrl+Shift+U` (when text input is focused and not in readonly mode)
- Delete one character to the right: `Ctrl+'` (when text input is focused and not in readonly mode)
- Delete one character to the left: `Ctrl+;` (when text input is focused and not in readonly mode)
- Cut line or selection region: `Cmd+K Cmd+K` (when editor text is focused)
- Paste line or selection region: `Cmd+Y Cmd+Y`

### LINE MOVEMENTS

- Move cursor right by one character: `Ctrl+L` (when text input is focused)
- Move cursor left by one character: `Ctrl+H` (when text input is focused)
- Move cursor up by one character: `Ctrl+K` (when text input is focused)
- Move cursor down by one character: `Ctrl+J` (when text input is focused)
- Move cursor right by one word: `Alt+L` (when text input is focused)
- Move cursor left by one word: `Alt+H` (when text input is focused)
- Move cursor to the end of the line: `Cmd+L` (when editor text is focused)
- Move cursor to the beginning of the line: `Cmd+H` (when editor text is focused)
- Move cursor up by function: `Ctrl+Shift+K` (when editor text is focused)
- Move cursor down by function: `Ctrl+Shift+J` (when text input is focused)

### LINE EXTRACTOR

- Duplicate line up: `Shift+Alt+K` (when editor text is focused)
- Duplicate line down: `Shift+Alt+J` (when editor text is focused)
- Move line up: `Alt+K` (when editor text is focused)
- Move line down: `Alt+J` (when editor text is focused)

### PAGE MOVEMENTS

- Move cursor up by one page: `Ctrl+P` (when text input is focused)
- Move cursor down by one page: `Ctrl+N` (when text input is focused)
- Move cursor up by function: `Ctrl+9` (when editor text is focused)
- Move cursor down by function: `Ctrl+0` (when editor text is focused)

### SELECTIONS

- Select one character to the right: `Ctrl+Shift+L` (when editor text is focused)
- Select one character to the left: `Ctrl+Shift+H` (when editor text is focused)
- Select word to the right: `Alt+Shift+L` (when text input is focused)
- Select word to the left: `Alt+Shift+H` (when text input is focused)
- Select line to the right: `Cmd+Shift+L` (when text input is focused)
- Select line to the left: `Cmd+Shift+H` (when text input is focused)
- Select line up: `Cmd+Shift+K` (when text input is focused)
- Select line down: `Cmd+Shift+J` (when text input is focused)

### VSCODE DEFAULT DISABLES

These key bindings disable some of the default Visual Studio Code key bindings:

- Disable deleting lines: `Shift+Cmd+K` (when text input is focused and not in readonly mode)
- Disable toggling query details in search: `Shift+Cmd+J` (when in search editor or search viewlet is focused)
- Disable deleting files: `Alt+Cmd+Backspace` (when files explorer is focused, folders view is visible, and resources are not readonly and input is not focused)
- Disable deleting all characters to the left: `Cmd+Backspace` (when text input is focused and not in readonly mode)
- Disable last editor in group: `Ctrl+0`

Feel free to customize these key bindings further to suit your preferences and workflow.

Happy coding!
