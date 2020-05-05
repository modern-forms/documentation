---

title: ListBox Class

---

# ListBox Class

Represents a ListBox control.

```csharp
public class ListBox : Control 
```

## Constructors

<table>
<tr><td>ListBox ()</td><td>Initializes a new instance of the ListBox class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>DefaultCursor</td><td>Gets the default cursor.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>FirstVisibleIndex</td><td>Gets or sets the index of the first visible item.</td></tr>
<tr><td>ItemHeight</td><td>Gets or sets the unscaled height each item will use.</td></tr>
<tr><td>Items</td><td>Gets the collection of items contained by this ListBox.</td></tr>
<tr><td>ScaledItemHeight</td><td>Gets the scaled height each item occupies.</td></tr>
<tr><td>ScrollbarAlwaysVisible</td><td>Gets or sets a value indicating if the vertical scrollbar is always shown.</td></tr>
<tr><td>SelectedIndex</td><td>Gets or sets the index of the currently selected item.  If there are multiple selected items, the first item's index will be returned.</td></tr>
<tr><td>SelectedItem</td><td>Gets or sets the currently selected item, if any.  If there are multiple selected items, the first selected item will be returned.</td></tr>
<tr><td>SelectedItems</td><td>Gets all currently select items.</td></tr>
<tr><td>SelectionMode</td><td>Gets or set the selection mode of the ListBox.</td></tr>
<tr><td>ShowHover</td><td>Gets or sets whether the item currently containing the mouse pointer should be highlighted.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>VisibleItemCount</td><td>The number of full items that can be shown at a time.</td></tr>
</table>

## Methods

<table>
<tr><td>GetIndexAtLocation (Point)</td><td>Gets the index of the item currently at the specified location.</td></tr>
<tr><td>GetItemRectangle (Int32)</td><td>Gets the bounding rectangle for the specified item.</td></tr>
<tr><td>OnMouseDown (MouseEventArgs)</td><td>Raises the MouseDown event.</td></tr>
<tr><td>OnMouseLeave (EventArgs)</td><td>Raises the MouseLeave event.</td></tr>
<tr><td>OnMouseMove (MouseEventArgs)</td><td>Raises the MouseMove event.</td></tr>
<tr><td>OnMouseWheel (MouseEventArgs)</td><td>Raises the MouseWheel event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnSelectedIndexChanged (EventArgs)</td><td>Raises the SelectedIndexChanged event.</td></tr>
<tr><td>SetBoundsCore (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>A version of SetBounds that can be overridden by subclasses.</td></tr>
</table>

## Events

<table>
<tr><td>SelectedIndexChanged</td><td>Raised when the value of the SelectedIndex property changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

