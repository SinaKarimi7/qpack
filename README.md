# Quality/Metric Extension Pack (QPack)

### QPack

Web Quality/Metric Development Essentials Extension Pack for Visual Studio Code

> These are some of my favorite extensions which helped me to keep to check the quality of my code.

### 1-Click Setup:

1. Press `ctrl+shift+p`
2. Type `qpack` or `update config`
3. Click on `Update Quality/Metric Extension Pack (QPack) Config` to automatically add below configs to your `settings.json` file
<details>
<summary>
<i>Click to see what configs this plugin will use</i>
</summary>

```json
{
  "cSpell.userWords": [],
  "eslint.alwaysShowStatus": true,
  "eslint.codeAction.showDocumentation": {
    "enable": true
  },
  "eslint.lintTask.enable": true,
  "errorLens.statusBarMessageEnabled": true,
  "errorLens.scrollbarHackEnabled": true,
  "errorLens.fontStyleItalic": true,
  "errorLens.statusBarColorsEnabled": true,
  "errorLens.addNumberOfDiagnostics": true,
  "errorLens.addAnnotationTextPrefixes": true,
  "errorLens.gutterIconsEnabled": true,
  "errorLens.followCursor": "closestProblem"
}
```

</details>

**Notes**:

- To enable `Sonar lint`, you have to install `java runtime environment(jre)`, which it will ask to download it when it has been installed.

- You can use [Tech Debt Metrics](https://marketplace.visualstudio.com/items?itemName=Stepsize.tech-debt-tracker) as a complement to `CodeMetrics` metric checker(But it is heavy).

## Extensions Included

- 1- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint JavaScript into VS Code.

- 2- [CodeMetrics](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-codemetrics) - Computes complexity in TypeScript / JavaScript files.

- 3- [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode) - SonarLint is an IDE extension that helps you detect and fix quality issues as you write code in JavaScript, TypeScript, Python, Java, HTML and PHP.

- 4- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - Spelling checker for source code

- 5- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) - Improve highlighting of errors, warnings and other language diagnostics.

- 6- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost) - Display import/require package size in the editor

## Recommended Extension pack

<a href="https://marketplace.visualstudio.com/items?itemName=SeyyedKhandon.zpack">
<img src="https://seyyedkhandon.gallerycdn.vsassets.io/extensions/seyyedkhandon/zpack/1.0.6/1620297423398/Microsoft.VisualStudio.Services.Icons.Default" width="300"/></a>

[ZPack](https://marketplace.visualstudio.com/items?itemName=SeyyedKhandon.zpack) is An Opinionated collection of the `best` and `most` used extensions for Web Developers in VSCode which has Better `Developer Experience(DX)` and `load time` in Mind.

## Relevant Links

- [Github](https://github.com/SeyyedKhandon/qpack)
- [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=SeyyedKhandon.qpack)

**Enjoy!**
