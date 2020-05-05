---

title: CheckBox Class

---

# CheckBox Class

Represents a CheckBox control.

```csharp
public class CheckBox : Control 
```

## Constructors

<table>
<tr><td>CheckBox ()</td><td>Initializes a new instance of the CheckBox class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td>The default ControlStyle for all instances of CheckBox.</td></tr>
</table>

## Properties

<table>
<tr><td>AutoCheck</td><td>Gets or sets a valud indicating if the CheckBox will respond to mouse clicks.</td></tr>
<tr><td>Checked</td><td>Gets or sets a value indicating if the CheckBox is in the checked state.</td></tr>
<tr><td>CheckState</td><td>Gets or sets the current state of the CheckBox.</td></tr>
<tr><td>DefaultCursor</td><td>Gets the default cursor.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>ThreeState</td><td>Gets or sets a value indicating whether the CheckBox will allow three check states rather than two.</td></tr>
</table>

## Methods

<table>
<tr><td>OnCheckedChanged (EventArgs)</td><td>Raises the CheckedChanged event.</td></tr>
<tr><td>OnCheckStateChanged (EventArgs)</td><td>Raises the CheckStateChanged event.</td></tr>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
</table>

## Events

<table>
<tr><td>CheckedChanged</td><td>Raised when the value of the Checked property changes.</td></tr>
<tr><td>CheckStateChanged</td><td>Raised when the value of the CheckState property changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

