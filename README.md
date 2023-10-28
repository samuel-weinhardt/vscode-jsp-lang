# JSP Language Support

This extension provides basic syntax highlighting support for Jakarta Server Pages (JSP; formerly JavaServer Pages) in VS Code.

## Limitations

Some JSP patterns are not handled correctly, such as [fragmented scriptlets](https://github.com/jakartaee/pages/blob/master/spec/src/main/asciidoc/ServerPages.adoc#1122-scriptlets). For example:

```jsp
 <% if
 (Calendar.getInstance().get(Calendar.AM_PM) == Calendar.AM) {%>
 Good Morning
 <% } else { %>
 Good Afternoon
 <% } %>
```

Contributions are welcome. Please open a pull request.
