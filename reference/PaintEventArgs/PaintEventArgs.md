---

title: PaintEventArgs Class

---

# PaintEventArgs Class

Provides data for the Paint event.

```csharp
public class PaintEventArgs : EventArgs 
```

## Constructors

<table>
<tr><td>PaintEventArgs (SKImageInfo, SKCanvas, Double)</td><td>Initializes a new instance of the PaintEventArgs class.</td></tr>
</table>

## Properties

<table>
<tr><td>Canvas</td><td>Gets the canvas needed to paint the control.</td></tr>
<tr><td>Info</td><td>Gets information about the image canvas.</td></tr>
<tr><td>Scaling</td><td>Gets the current scale factor of the form.</td></tr>
</table>

## Methods

<table>
<tr><td>LogicalToDeviceUnits (Int32)</td><td>Transforms a horizontal or vertical integer coordinate from logical to device units
            by scaling it up for current DPI and rounding to nearest integer value.</td></tr>
<tr><td>LogicalToDeviceUnits (Size)</td><td>Transforms a Size from logical to device units
            by scaling it up for current DPI and rounding to nearest integer value.</td></tr>
<tr><td>LogicalToDeviceUnits (Padding)</td><td>Transforms a Padding from logical to device units
            by scaling it up for current DPI and rounding to nearest integer value.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

