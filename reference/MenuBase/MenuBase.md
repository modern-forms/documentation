---

title: MenuBase Class

---

# MenuBase Class

Represents a base class for all Menu related controls.

```csharp
public abstract class MenuBase : Control 
```

## Constructors

<table>
<tr><td>MenuBase ()</td><td>Initializes a new instance of the MenuBase class.</td></tr>
<tr><td>MenuBase (MenuItem)</td><td>Initializes a new instance of the MenuBase class with the provided root MenuItem.</td></tr>
</table>

## Properties

<table>
<tr><td>IsActivated</td><td>Gets a value indicating if the Menu is currently visible.</td></tr>
<tr><td>IsReleaseOnClick</td><td>Gets a value indicating the Menu should close on click.</td></tr>
<tr><td>IsTopLevelMenu</td><td>Gets a value indicating this is a top level menu.</td></tr>
<tr><td>Items</td><td>Gets the collection of menu items contained by this Menu.</td></tr>
<tr><td>SelectedItem</td><td>Gets or sets the currently selected menu item.</td></tr>
</table>

## Methods

<table>
<tr><td>GetItemAtLocation (Point)</td><td>Get the MenuItem at the specified location.</td></tr>
<tr><td>GetTopLevelMenu ()</td><td>Get the top level Menu control, if any.</td></tr>
<tr><td>LayoutItems ()</td><td>Lays out the child menu items.</td></tr>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnHoverChanged (MenuItem, MenuItem)</td><td>Raises the HoverChanged event.</td></tr>
<tr><td>OnItemClicked (MouseEventArgs, MenuItem)</td><td>Raises the ItemClicked event.</td></tr>
<tr><td>OnMouseLeave (EventArgs)</td><td>Raises the MouseLeave event.</td></tr>
<tr><td>OnMouseMove (MouseEventArgs)</td><td>Raises the MouseMove event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

