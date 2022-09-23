# vscode-extensions
A list of my current VS Code extensions

## Installation
The below examples will install ```extensions.list``` which include theming. Please use the ```extensions-without-theme.list``` file in the installation commands if you'd like to avoid installing themes.

### Windows using Powershell

```cat extensions.list |% { code --install-extension $_}```

### Linux using Bash (works on macOS and WSL)

```cat extensions.list | xargs code --list-extensions {}```

