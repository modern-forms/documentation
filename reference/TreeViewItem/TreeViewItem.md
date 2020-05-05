---

title: TreeViewItem Class

---

# TreeViewItem Class

Represents a TreeViewItem.

```csharp
public class TreeViewItem : ILayoutable 
```

## Constructors

<table>
<tr><td>TreeViewItem ()</td><td>Initializes a new instance of the TreeViewItem class.</td></tr>
<tr><td>TreeViewItem (String)</td><td>Initializes a new instance of the TreeViewItem class with the specified text.</td></tr>
<tr><td>TreeViewItem (String, TreeViewItem[])</td><td>Initializes a new instance of the TreeViewItem class with the specified text and child nodes.</td></tr>
</table>

## Properties

<table>
<tr><td>Bounds</td><td>Gets the current bounding box of the tab.</td></tr>
<tr><td>ContextMenu</td><td>Gets or sets a context menu to display when the item is right-clicked.</td></tr>
<tr><td>Expanded</td><td>Gets or sets a value indicating this node is showing its child nodes.</td></tr>
<tr><td>HasChildren</td><td>Gets a value indicating whether this item contains child items.</td></tr>
<tr><td>Image</td><td>Gets or sets the image of the item.</td></tr>
<tr><td>IndentLevel</td><td>Gets a value indicating how many levels this item is nested from the root.</td></tr>
<tr><td>Items</td><td>Gets the collection of child nodes.</td></tr>
<tr><td>Margin</td><td>Gets the amount of margin to leave around this item. This is internal API and should not be called.</td></tr>
<tr><td>Parent</td><td>The parent item that contains this item.</td></tr>
<tr><td>Selected</td><td>Gets or sets a value indicating this item is currently selected.</td></tr>
<tr><td>Tag</td><td>Gets or sets an object with additional user data about this item.</td></tr>
<tr><td>Text</td><td>Gets or sets the text of the item.</td></tr>
<tr><td>TreeView</td><td>Gets the TreeView that contains this item.</td></tr>
</table>

## Methods

<table>
<tr><td>GetPreferredSize (Size)</td><td>Gets the preferred size of the tab.</td></tr>
<tr><td>SetBounds (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>Sets the bounding box of the tab. This is internal API and should not be called.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

