<h3 align="center">CoderJibon</h3>
  <h3 align="center">My Visual Studio Code Settings & Extensions</h3>

## vs-code-extensions.text

Extensions

1. Live Server - ritwik dey
2. ES Lint - Dirk Baeumer
3. Code Spell Checker
4. JavaScript (ES6) code snippets
5. Material Icon Theme
6. Prettier - Code formatter - Esben Petersen
7. Path Autocomplete - Mihai Vilcu
8. Turbo Console Log - ChakrounAnas
9. ES7 React/Redux/GraphQL/React-Native snippets - dsznajder
10. Dracula Official - Dracula Theme
11. Auto Rename Tag - Jun Han
12. Andromeda - Eliver Lara
13. Emoji Snippets - Devzstudio
14. Community Material Theme - Mattia Astorino
15. Auto Import

## vs-code-setting.json file

{
// editor
"editor.fontSize": 20,
"editor.fontFamily": "Fira Code, Operator Mono",
"editor.fontLigatures": true,
"editor.wordWrap": "on",
"editor.minimap.enabled": false,
"editor.tokenColorCustomizations": {
"textMateRules": [
{
"scope": "comment",
"settings": {
"fontStyle": "normal"
}
}
]
},
// cursor
"editor.cursorSmoothCaretAnimation": true,
"editor.cursorBlinking": "expand",
// config related to code formatting
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.formatOnSave": true,
"[javascript]": {
"editor.formatOnSave": false,
"editor.defaultFormatter": null
},
"[javascriptreact]": {
"editor.formatOnSave": false,
"editor.defaultFormatter": null
},
"editor.codeActionsOnSave": {
"source.fixAll.eslint": true,
"source.fixAll.tslint": true,
"source.organizeImports": true
},
"eslint.alwaysShowStatus": true,
//terminal
"terminal.integrated.fontSize": 16,
"terminal.integrated.fontWeight": "normal",
"terminal.integrated.fontFamily": "Fira Code, Operator Mono",
"workbench.colorTheme": "Community Material Theme Darker High Contrast",
"workbench.iconTheme": "vscode-icons",
// terminal customization
"workbench.colorCustomizations": {
"terminal.background": "#1D2021",
"terminal.foreground": "#A89984",
"terminalCursor.background": "#A89984",
"terminalCursor.foreground": "#A89984",
"terminal.ansiBlack": "#1D2021",
"terminal.ansiBlue": "#0D6678",
"terminal.ansiBrightBlack": "#665C54",
"terminal.ansiBrightBlue": "#0D6678",
"terminal.ansiBrightCyan": "#8BA59B",
"terminal.ansiBrightGreen": "#95C085",
"terminal.ansiBrightMagenta": "#8F4673",
"terminal.ansiBrightRed": "#FB543F",
"terminal.ansiBrightWhite": "#FDF4C1",
"terminal.ansiBrightYellow": "#FAC03B",
"terminal.ansiCyan": "#8BA59B",
"terminal.ansiGreen": "#95C085",
"terminal.ansiMagenta": "#8F4673",
"terminal.ansiRed": "#FB543F",
"terminal.ansiWhite": "#A89984",
"terminal.ansiYellow": "#FAC03B"
}
}
