# Ginko Ginko

<p align="center">
    <a href="https://marketplace.visualstudio.com/items?itemName=MosseSox.ginko-ginko">
        <img src="https://vsmarketplacebadges.dev/version-short/MosseSox.ginko-ginko.jpg?style=for-the-badge&colorA=252526&colorB=1B9AAA&label=Version" alt="Version">
    </a>&nbsp;
    <a href="https://marketplace.visualstudio.com/items?itemName=MosseSox.ginko-ginko">
        <img src="https://vsmarketplacebadges.dev/rating-short/MosseSox.ginko-ginko.jpg?style=for-the-badge&colorA=252526&colorB=1B9AAA&label=Rating" alt="Rating">
    </a>&nbsp;
    <a href="https://marketplace.visualstudio.com/items?itemName=MosseSox.ginko-ginko">
        <img src="https://vsmarketplacebadges.dev/installs-short/MosseSox.ginko-ginko.jpg?style=for-the-badge&colorA=252526&colorB=1B9AAA&label=Installs" alt="Installs">
    </a>&nbsp;
    <a href="https://marketplace.visualstudio.com/items?itemName=MosseSox.ginko-ginko">
        <img src="https://vsmarketplacebadges.dev/downloads-short/MosseSox.ginko-ginko.jpg?style=for-the-badge&colorA=252526&colorB=1B9AAA&label=Downloads" alt="Downloads">
    </a>
</p>

#### A color theme based on ginko leaves in the fall on a sunny day. Enjoy!

<br/>
Note: this theme is still in development - some tokens are colored green until they can be located. If you find green text, please file an issue <a href='https://github.com/Mosse-Sox/ginko-ginko/issues'>here</a>.

<hr/>
## Preview

- Javascript
  ![ginko ginko js highlighing](https://github.com/Mosse-Sox/ginko-ginko/blob/main/images/jsginko.png?raw=true)

- Typescript/tsx
  ![ginko ginko ts highlighing](https://github.com/Mosse-Sox/ginko-ginko/blob/main/images/typescriptginko.png?raw=true)

<hr/>

## Getting Started

### 1. Install and select theme

- Download and install the theme
- Go to the manage icon (the cog wheel) and select Themes > Color Theme
- Select Ginko Ginko from the list

### 2. Change bracket colors to match theme or your prefernce

- Go to the manage icon again and select Settings
- Open the JSON version of your user settings
- Paste this code in and experiment with the colors!

```json
{
  "[jsonc]": {
    "editor.bracketPairColorization.enabled": true,
    "workbench.colorCustomizations": {
      "editorBracketHighlight.foreground1": "#3684c4",
      "editorBracketHighlight.foreground2": "#e68f43",
      "editorBracketHighlight.foreground3": "#f84465",
      "editorBracketHighlight.foreground4": "#1f8124",
      "editorBracketHighlight.foreground5": "#ad1b1b",
      "editorBracketHighlight.foreground6": "#333d51",
      "editorBracketHighlight.unexpectedBracket.foreground": "#ff878b"
    }
  }
}
```
