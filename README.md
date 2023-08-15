### I needed extension tailored for my own needs. For now, the extension is private but I will make it Open Source soon, contributions will be welcome! :)
LINK: https://marketplace.visualstudio.com/items?itemName=Kapunac.console-everything

# Console Everything Visual Studio Code Extension

This Visual Studio Code extension allows you to quickly insert `console.log` statements into your code. It provides a convenient way to add logging statements for debugging and monitoring purposes.

## Features

- Press `Alt+Q` to insert a `console.log` statement at the current position.
- The inserted `console.log` statement will display the line number where it is being triggered. For example: `console.log('Line 13.')`.
- If you have a selection, the extension will attempt to determine the type of the selection (function, array, object, or variable). It will include the selected text as an additional parameter in the `console.log` statement. For example: `console.log('Line 13. Object: employeesObj', employeesObj)`.
- The extension intelligently adds the `console.log` statement below the closing brackets of the selected code block if applicable.

## Beta Testing

This extension is currently in beta testing. It was initially developed for personal use but is now being shared with the community. Your feedback and suggestions are highly appreciated as they will help improve the extension further.

## Installation

1. Launch Visual Studio Code.
2. Go to the Extensions view by clicking on the square icon on the left sidebar or pressing `Ctrl+Shift+X`.
3. Search for "Console Log Extension" and click on "Install".
4. Once installed, you can start using the extension.

## Usage

To insert a `console.log` statement:

1. Place the cursor at the desired location or select the code block you want to add the `console.log` to.
2. Press `Alt+Q` to insert the `console.log` statement.

## Feedback

If you encounter any issues, have suggestions, or want to contribute you can reach out to me on email: vnkapunac@gmail.com
