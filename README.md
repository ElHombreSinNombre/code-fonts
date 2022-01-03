# Code fonts

This a simple mashups of the **[Victor Mono](https://github.com/rubjo/victor-mono)** and **[Fira Code](https://github.com/tonsky/FiraCode)** fonts.

We create this mix with **[FontForge](https://fontforge.org/en-US/downloads/)**.

![Example](img/code.png)

After all we can customize settings adding something like this (**Visual Code** example).


    "editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
    "editor.tokenColorCustomizations": {
      "textMateRules": [
        {
          "scope": "emphasis",
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "scope": "strong",
          "settings": {
            "fontStyle": "bold"
          }
        },
        {
          "scope": "entity.other.attribute-name",
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "scope": "markup.underline",
          "settings": {
            "fontStyle": "underline"
          }
        },
        {
          "scope": "markup.bold",
          "settings": {
            "fontStyle": "bold"
          }
        },
        {
          "scope": "markup.heading",
          "settings": {
            "fontStyle": "bold"
          }
        },
        {
          "scope": "markup.italic",
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "name": "String interpolation",
          "scope": [
            "punctuation.definition.template-expression.begin",
            "punctuation.definition.template-expression.end",
            "punctuation.section.embedded"
          ],
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "name": "@Decorator",
          "scope": ["meta.decorator punctuation.decorator"],
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "scope": ["punctuation.definition.comment", "comment"],
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "scope": [
            "entity.name.type.class", 
            "keyword", 
            "constant", 
            "storage.modifier", 
            "storage.type",
            "storage.type.class.js", 
          ],
          "settings": {
            "fontStyle": "italic"
          }
        },
        {
          "scope": [
            "invalid",
            "keyword.operator",
            "constant.numeric.css",
            "keyword.other.unit.px.css",
            "constant.numeric.decimal.js",
            "constant.numeric.json"
          ],
          "settings": {
            "fontStyle": ""
          }
        }
      ]
    },
