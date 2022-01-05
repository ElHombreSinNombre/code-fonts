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
              "entity.name.function",
              "keyword",
              "entity.other",
              //"comment",
              "support.class",
              "support.other.namespace",
              "support.function",
              "variable.language.this",
              "meta.import",
              "this",
              "meta.function-call",
              "punctuation.section.tag",
            ],
            "settings": {
              "fontStyle": "italic"
            }
          },
          {
            "scope": [
              "variable.other",
              "entity.name.function"
            ],
            "settings": {
              "fontStyle": ""
            }
          },
        ]
      },

We can identify the elements in **Visual Code** with 

> ctrl + shift + p

And search *Inspect Editor Tokens and Scopes* 

![Token](img/token.jpg)
