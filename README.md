# Visual Studio Code - Personal Setup

A place to keep track of my favorite settings &amp; extensions for [Visual Studio Code](https://code.visualstudio.com/). For more awesome packages and resources, check out [awesome-vscode](https://github.com/viatsko/awesome-vscode)

## Table of Contents

- [Settings](#settings)
- [Extensions](#extensions)

## Settings

_VS Code provides two different scopes for settings:_

- _**User Settings** - Settings that apply globally to any instance of VS Code you open_
- _**Workspace Settings** - Settings stored inside your workspace and only apply when the workspace is opened_

### To open your User Settings JSON file:

- Open the Command Palette (⇧⌘P)
- Execute the command: "Preferences: Open Settings (JSON)"

### To modify settings, reference: [settings.json](./settings.json)

## Extensions

### Links

- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)

### Code CLI

_You can install and manage VS Code extensions from the command line_

**To List all currently installed extensions**

```
code --list-extensions
```

> My output from \$code --list-extensions:
>
> ```
> CoenraadS.bracket-pair-colorizer-2
> eamodio.gitlens
> Equinusocio.vsc-material-theme
> esbenp.prettier-vscode
> ms-vscode.vscode-typescript-tslint-plugin
> naumovs.color-highlight
> oderwat.indent-rainbow
> PKief.material-icon-theme
> vincaslt.highlight-matching-tag
> wix.vscode-import-cost
> ```

**To install an extension. Provide the full extension name publisher.extension as an argument. Use --force argument to avoid prompts**

```
code --install-extension <ext
```

> To install all of the linked extensions, you can run:
>
> ```
> code --install extension CoenraadS.bracket-pair-colorizer-2
> code --install extension eamodio.gitlens
> code --install extension Equinusocio.vsc-material-theme
> code --install extension esbenp.prettier-vscode
> code --install extension ms-vscode.vscode-typescript-tslint-plugin
> code --install extension naumovs.color-highlight
> code --install extension oderwat.indent-rainbow
> code --install extension PKief.material-icon-theme
> code --install extension vincaslt.highlight-matching-tag
> code --install extension wix.vscode-import-cost
> ```

**To uninstall an extension. Provide the full extension name publisher.extension as an argument**

```
code --uninstall-extension <ext
```

> To uninstall all of the linked extensions, you can run:
>
> ```
> code --uninstall extension CoenraadS.bracket-pair-colorizer-2
> code --uninstall extension eamodio.gitlens
> code --uninstall extension Equinusocio.vsc-material-theme
> code --uninstall extension esbenp.prettier-vscode
> code --uninstall extension ms-vscode.vscode-typescript-tslint-plugin
> code --uninstall extension naumovs.color-highlight
> code --uninstall extension oderwat.indent-rainbow
> code --uninstall extension PKief.material-icon-theme
> code --uninstall extension vincaslt.highlight-matching-tag
> code --uninstall extension wix.vscode-import-cost
> ```
