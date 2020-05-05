---

title: PictureBox Class

---

# PictureBox Class

Represents a PictureBox control.

```csharp
public class PictureBox : Control 
```

## Constructors

<table>
<tr><td>PictureBox ()</td><td>Initializes a new instance of the PictureBox class.</td></tr>
</table>

## Properties

<table>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>Image</td><td>Gets or sets the image the PictureBox should display.</td></tr>
<tr><td>ImageLocation</td><td>Gets or sets the path or URL of the image the PictureBox should display.</td></tr>
<tr><td>IsErrored</td><td>Gets a value indicating the requested image could not be loaded.</td></tr>
<tr><td>SizeMode</td><td>Gets or sets a value indicated the sizing mode used.</td></tr>
</table>

## Methods

<table>
<tr><td>Load (String)</td><td>Loads the image at the specified path or URL and sets ImageLocation to it.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnSizeModeChanged (EventArgs)</td><td>Raises the SizeModeChanged event.</td></tr>
</table>

## Events

<table>
<tr><td>SizeModeChanged</td><td>Raised when the value of the SizeMode property changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

