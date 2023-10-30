# Theme Shadow Frost

## Author

- [@BidyutKrDas](https://github.com/Bidyut-Kr-Das)

### Steps to install the extension locally in vs code

(incase you can not find it in vscode extension)

~**Run the following commands**

1. _Clone the repository_

```bash
   git clone https://github.com/Bidyut-Kr-Das/VsCode-Theme.git
```

2. _Change the current terminal directory to VsCode-Theme_

```bash
   cd .\VsCode-Theme
```

3. _Install the vsce module to create the extension_

```bash
   npm i -g vsce
```

4. _Create the extension using vsce_

```bash
   vsce package
```

_Install the extension_(replace the `<version>` with version of your .vsix file)

```bash
   code --install-extension shadowfrost-theme-<version>.vsix
```
