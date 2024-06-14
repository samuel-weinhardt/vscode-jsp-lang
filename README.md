# JSP Language Support

This extension provides basic syntax highlighting support for Jakarta Server Pages (JSP; formerly JavaServer Pages) in VS Code.

Note that not all JSP patterns are handled. Contributions are welcome. Please open a pull request.

![Example image](./assets/example.png)

To enable [emmet abbreviations](https://code.visualstudio.com/docs/editor/emmet#_emmet-abbreviations-in-other-file-types) for JSP files (for example, to expand `h1` to `<h1></h1>`), add the following configuration to your settings:

```json
"emmet.includeLanguages": {
    "jsp": "html"
}
```
