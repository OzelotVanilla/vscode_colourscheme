# vscode_colourscheme
The colour scheme fit for [Quiet Light]

Mwno is the colour scheme. Please be careful *not* to overwrite our original settings.
The position of Mwno should like this:


```jsonc
{    // <---- This is the outer bracket of settings.json
    "workbench.colorTheme": "Quiet Light",
    "editor.wordWrap": "on",
    "editor.minimap.enabled": false,
    "workbench.colorCustomizations": {
        "[Quiet Light]": {
            "editorBracketHighlight.foreground1": "#daa520", // Goldenrod
            "editorBracketHighlight.foreground2": "#da70d6", //Orchid
            "editorBracketHighlight.foreground3": "#6459ed" // CornFlowerBlue
        }
    },
    "editor.semanticTokenColorCustomizations": {
        "enabled": true,
        "[Quiet Light]": {
            "rules": {
                "label": {
                    "foreground": "#028760",
                    "fontStyle": "bold"
                },
                "property": {
                    "foreground": "#d9a62e",
                    "fontStyle": ""
                },
......
```

For your convenience, you can go to raw code page, select all, then copy-paste to your settings,
the paste position is inside the first brace.

If your `settings.json` is empty, first create a pair of brace `{}`, then paste into it.
