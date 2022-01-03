# Code fonts

This a simple mashups of the **[Victor Mono](https://github.com/rubjo/victor-mono)** and **[Fira Code](https://github.com/tonsky/FiraCode)** fonts.

We create this mix with **[FontForge](https://fontforge.org/en-US/downloads/)**.

![Example](img/code.png)

After all we can customize settings adding something like this (**Visual Code** example).


    "editor.tokenColorCustomizations": {
        "textMateRules": [
          {
            "scope": [
              "markup.heading",
              "markup.bold"
            ],
            "settings": {
              "fontStyle": "bold"
            }
          },
          {
            "scope": [
              "strong",
              "emphasis",
              "entity.other.attribute-name",
              "markup.italic",
              "punctuation.definition.template-expression.begin",
              "punctuation.definition.template-expression.end",
              "punctuation.section.embedded",
              "meta.decorator punctuation.decorator",
              "punctuation.definition.comment",
              "comment",
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
    }
