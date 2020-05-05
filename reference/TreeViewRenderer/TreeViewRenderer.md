---

title: TreeViewRenderer Class

---

# TreeViewRenderer Class

Represents a class that can render a TreeView.

```csharp
public class TreeViewRenderer : Renderer<TreeView> 
```

## Constructors

<table>
<tr><td>TreeViewRenderer ()</td><td></td></tr>
</table>

## Fields

<table>
<tr><td>GLYPH_SIZE</td><td>Size of dropdown glyph.</td></tr>
<tr><td>IMAGE_SIZE</td><td>Size of item image.</td></tr>
<tr><td>INDENT_SIZE</td><td>Size of each indent level.</td></tr>
</table>

## Methods

<table>
<tr><td>GetGlyphBounds (TreeView, TreeViewItem)</td><td>Gets the bounds of the dropdown glyph.</td></tr>
<tr><td>GetImageBounds (TreeView, TreeViewItem, PaintEventArgs)</td><td>Gets the bounds of the item image.</td></tr>
<tr><td>GetIndentStart (TreeView, TreeViewItem)</td><td>Gets the left start of the item bounds, accounting for indent level.</td></tr>
<tr><td>GetShouldDrawDropdownGlyph (TreeView, TreeViewItem)</td><td>Gets if the item should draw a dropdown glyph.</td></tr>
<tr><td>GetTextBounds (TreeView, TreeViewItem, PaintEventArgs)</td><td>Gets the bounds of the item text.</td></tr>
<tr><td>Render (TreeView, PaintEventArgs)</td><td>Renders the control.</td></tr>
<tr><td>RenderItem (TreeView, TreeViewItem, PaintEventArgs)</td><td>Renders a TreeViewItem.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

