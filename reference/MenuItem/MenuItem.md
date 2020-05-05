---

title: MenuItem Class

---

# MenuItem Class

Represents a MenuItem menu item.

```csharp
public class MenuItem : ILayoutable 
```

## Constructors

<table>
<tr><td>MenuItem ()</td><td>Initializes a new instance of the MenuItem class.</td></tr>
<tr><td>MenuItem (String, SKBitmap, EventHandler`1)</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>Bounds</td><td>Gets the bounding box of this menu item.</td></tr>
<tr><td>Enabled</td><td>Gets or sets a value indicating whether the menu item is enabled.</td></tr>
<tr><td>HasItems</td><td>Gets a value indicating if this menu item has any child items.</td></tr>
<tr><td>Hovered</td><td>Gets a value indicating the mouse cursor is currently hovering over this menu item.</td></tr>
<tr><td>Image</td><td>Gets or sets an image to be displayed on the menu item.</td></tr>
<tr><td>IsDropDownOpened</td><td>Gets a value indicating this menu item's drop down is currently open.</td></tr>
<tr><td>Items</td><td>Gets the collection of menu items contained by this menu item.</td></tr>
<tr><td>Margin</td><td>Gets or sets the margin of this menu item.</td></tr>
<tr><td>Padding</td><td>Gets or sets the amount of padding to apply to the menu item.</td></tr>
<tr><td>Parent</td><td>The parent menu item this item belongs to, if any.</td></tr>
<tr><td>Selected</td><td>Gets a value indicating if this menu item is currently selected.</td></tr>
<tr><td>Text</td><td>Gets or sets the text of the menu item.</td></tr>
</table>

## Methods

<table>
<tr><td>GetPreferredSize (Size)</td><td>Returns a preferred size the menu item would like to be.</td></tr>
<tr><td>HideDropDown ()</td><td>Closes the menu item's drop down.</td></tr>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the Click event.</td></tr>
<tr><td>SetBounds (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>Sets the bounds of the menu item. This API is considered internal and is not intended for public use.</td></tr>
<tr><td>ShowDropDown ()</td><td>Shows this menu items drop down, if any.</td></tr>
</table>

## Events

<table>
<tr><td>Click</td><td>Raised when the menu item is clicked.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

