# Code fonts

This a simple mashups of the **[Victor Mono](https://github.com/rubjo/victor-mono)** and **[Fira Code](https://github.com/tonsky/FiraCode)** fonts.

We create this mix with **[FontForge](https://fontforge.org/en-US/downloads/)**.

![Example](img/code.png)

After all we can customize settings adding something like this in *settings.json* (**Visual Code** example).

    "editor.tokenColorCustomizations": {
        "textMateRules": [
          {
            "scope": [
              "markup.heading",
              "markup.bold",
              "strong",
            ],
            "settings": {
              "fontStyle": "bold"
            }
          },
          {
            "scope": [
              "markup.italic",
              "entity.name.type.class",
              "keyword",
              //"comment",
              //PHP
              "entity.other.inherited-class",
              "support.class",
              "support.other.namespace",
              "entity.name.function",
              "support.function",
              "variable.language.this",
              //JS
              "meta.import.ts meta.block.ts variable.other.readwrite.alias.ts",
              "meta.import.tsx meta.block.tsx variable.other.readwrite.alias.tsx",
              "meta.import.js variable.other",
              "meta.export.ts meta.block.ts variable.other.readwrite.alias.ts",
              "meta.export.tsx meta.block.tsx variable.other.readwrite.alias.tsx",
              "meta.export.js variable.other",  
              "this"
            ],
            "settings": {
              "fontStyle": "italic"
            }
          },
          
        ]
      },

We can identify the elements in **Visual Code** with 

> ctrl + shift + p

And search *Inspect Editor Tokens and Scopes* 

![Token](img/token.jpg)