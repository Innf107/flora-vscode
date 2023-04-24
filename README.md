# Flora

Syntax highlighting for the [Flora Programming Language](https://github.com/Innf107/flora).

## Features

Syntax Highlighting for `.flora` files.

## Build Instructions
To build and install flora-vscode, first install `vsce` (This has to be executed as root)
```
npm install -g vsce
```
To create the package `.vsix` file, run
```
vsce package
```
This will generate a file called `flora-<version>.vsix`.

In Visual Studio Code, press `Ctrl + P` to open the command prompt, type in
```
>Extensions: Install from VSIX
```
and select the generated `flora-<version>.vsix` file.

Now reload vscode via
```
>Developer: Reload Window
```
