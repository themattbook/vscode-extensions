# vscode-extensions
A list of my current VS Code extensions

## Installation
The below examples will install ```extensions.list``` which include theming. Please use the ```extensions-without-theme.list``` file in the installation commands if you'd like to avoid installing themes.

## Important
I've never tried importing an extensions list with extensions already installed on my machine. This may (or may not) cause conflicts. Use at your own risk.

### Windows using Powershell

```cat extensions.list |% { code --install-extension $_}```

### Linux using Bash (works on macOS and WSL)

```cat extensions.list | xargs code --list-extensions {}```

