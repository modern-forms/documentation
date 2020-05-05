---

title: ComboBox Class

---

# ComboBox Class

Represents a ComboBox control.

```csharp
public class ComboBox : Control 
```

## Constructors

<table>
<tr><td>ComboBox ()</td><td>Initializes a new instance of the ComboBox class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td>The default ControlStyle for all instances of ComboBox.</td></tr>
</table>

## Properties

<table>
<tr><td>DefaultCursor</td><td>Gets the default cursor.</td></tr>
<tr><td>DefaultPadding</td><td>Gets the default padding of the control.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>DroppedDown</td><td>Gets or sets whether the drop down portion of the ComboBox is currently shown.</td></tr>
<tr><td>Items</td><td>Gets the collection of items contained by this ComboBox.</td></tr>
<tr><td>SelectedIndex</td><td>Gets or sets the index of the currently selected item.  Returns -1 if no item is selected.</td></tr>
<tr><td>SelectedItem</td><td>Gets or sets the currently selected item, if any.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
</table>

## Methods

<table>
<tr><td>Dispose (Boolean)</td><td>Disposes unmanaged resources used by the control.</td></tr>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnDeselected (EventArgs)</td><td>Called when the control is deselected.</td></tr>
<tr><td>OnDropDownClosed (EventArgs)</td><td>Raises the DropDownOpened event.</td></tr>
<tr><td>OnDropDownOpened (EventArgs)</td><td>Raises the DropDownOpened event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnSelectedIndexChanged (EventArgs)</td><td>Raises the SelectedIndexChanged event.</td></tr>
</table>

## Events

<table>
<tr><td>DropDownClosed</td><td>Raised when the drop down portion of the ComboBox is closed.</td></tr>
<tr><td>DropDownOpened</td><td>Raised when the drop down portion of the ComboBox is opened.</td></tr>
<tr><td>SelectedIndexChanged</td><td>Raised when the value of the SelectedIndex property changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

