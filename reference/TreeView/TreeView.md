---

title: TreeView Class

---

# TreeView Class

Represents a TreeView control.

```csharp
public class TreeView : Control 
```

## Constructors

<table>
<tr><td>TreeView ()</td><td>Initializes a new instance of the TreeView class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>Items</td><td>Gets the collection of items contained by this TreeView.</td></tr>
<tr><td>SelectedItem</td><td>Gets or sets the currently selected TreeViewItem.</td></tr>
<tr><td>ShowDropdownGlyph</td><td>Gets or sets a value indicating the drop down glyph should be shown.</td></tr>
<tr><td>ShowItemImages</td><td>Gets or sets a value indicating item images should be shown.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>VirtualMode</td><td>Gets or sets a value indicating if TreeViewItem nodes will be resolved when expanded.</td></tr>
</table>

## Methods

<table>
<tr><td>GetItemAtLocation (Point)</td><td>Returns the TreeViewItem at the specified location.</td></tr>
<tr><td>OnBeforeExpand (EventArgs`1)</td><td></td></tr>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnDoubleClick (MouseEventArgs)</td><td>Raises the DoubleClick event.</td></tr>
<tr><td>OnItemSelected (EventArgs`1)</td><td></td></tr>
<tr><td>OnMouseWheel (MouseEventArgs)</td><td>Raises the MouseWheel event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>SetBoundsCore (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>A version of SetBounds that can be overridden by subclasses.</td></tr>
</table>

## Events

<table>
<tr><td>BeforeExpand</td><td>Raised before a node is expanded.</td></tr>
<tr><td>ItemSelected</td><td>Raised when an item is selected.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

