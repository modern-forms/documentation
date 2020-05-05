---

title: Ribbon Class

---

# Ribbon Class

Represents a Ribbon control.
            Note the Ribbon control has not been fully developed, and probably does not contain enough functionality to be useful yet.

```csharp
public class Ribbon : Control 
```

## Constructors

<table>
<tr><td>Ribbon ()</td><td>Initializes a new instance of the Ribbon class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>SelectedTabPage</td><td>Gets or sets the currently selected tab page.</td></tr>
<tr><td>SelectedTabPageIndex</td><td>Gets or sets the index of the currently selected tab page. This value will be -1 if there is not a selected tab page;</td></tr>
<tr><td>ShowTabs</td><td>Gets or sets a value indicating if the ribbon tabs are shown.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>TabPages</td><td>Gets the collection of tab pages contained by this Ribbon.</td></tr>
</table>

## Methods

<table>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnMouseLeave (EventArgs)</td><td>Raises the MouseLeave event.</td></tr>
<tr><td>OnMouseMove (MouseEventArgs)</td><td>Raises the MouseMove event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnSelectedTabPageIndexChanged (EventArgs)</td><td>Raises the SelectedTabPageIndexChanged event.</td></tr>
</table>

## Events

<table>
<tr><td>SelectedTabPageIndexChanged</td><td>Raised when the value of the SelectedTabPageIndex property changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

