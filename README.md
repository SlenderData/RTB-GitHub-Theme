# RTB-GitHub-Theme

一个可以去掉表格边框的 Typora GitHub 主题。

A Typora GitHub Theme with Removable Table Borders.

markdown 文档中无边框表格可以很方便地用于排版。

Borderless tables in markdown documents can be conveniently used for typesetting.

如需添加一个无边框的表格，请创建一个 `id="rtb"` 的 `div` 元素，并在其内部用 HTML 语法来完成表格。

To add a borderless table, create a `div` element with the `id="rtb"` and use HTML syntax inside to construct the table.

由于Typora本身的问题，在编辑 markdown 文档时，可能无法正确渲染无边框表格，而是以默认样式显示。然而，这不会影响导出的 PDF/HTML 文件。

Due to an issue with Typora itself, when editing markdown documents, it may not render borderless tables correctly, displaying them in the default style instead. However, this does not affect the exported PDF/HTML files.

## 使用示例 Usage Example

```html
<div id="rtb">
    <table>
        ...
    </table>
</div>
```
