---

title: ScrollBar Class

---

# ScrollBar Class

Represents the base class of a ScrollBar control.

```csharp
public abstract class ScrollBar : Control 
```

## Constructors

<table>
<tr><td>ScrollBar (Boolean)</td><td>Initializes a new instance of the ScrollBar class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>LargeChange</td><td>Gets or sets the amount the ScrollBar will change when clicked in the track area.</td></tr>
<tr><td>Maximum</td><td>Gets or sets the maximum value the ScrollBar will allow.</td></tr>
<tr><td>Minimum</td><td>Gets or sets the minimum value the ScrollBar will allow.</td></tr>
<tr><td>SmallChange</td><td>Gets or sets the amount the ScrollBar will change when the increment or decrement arrows are clicked.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>Value</td><td>Gets or sets the current value of the ScrollBar.</td></tr>
</table>

## Methods

<table>
<tr><td>OnMouseDown (MouseEventArgs)</td><td>Raises the MouseDown event.</td></tr>
<tr><td>OnMouseMove (MouseEventArgs)</td><td>Raises the MouseMove event.</td></tr>
<tr><td>OnMouseUp (MouseEventArgs)</td><td>Raises the MouseUp event.</td></tr>
<tr><td>OnMouseWheel (MouseEventArgs)</td><td>Raises the MouseWheel event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnScroll (ScrollEventArgs)</td><td>Raises the Scroll event.</td></tr>
<tr><td>OnSizeChanged (EventArgs)</td><td>Raises the SizeChanged event.</td></tr>
<tr><td>OnValueChanged (EventArgs)</td><td>Raises the ValueChanged event.</td></tr>
<tr><td>OnVisibleChanged (EventArgs)</td><td>Raises the VisibleChanged event.</td></tr>
<tr><td>SetBoundsCore (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>A version of SetBounds that can be overridden by subclasses.</td></tr>
</table>

## Events

<table>
<tr><td>Scroll</td><td>Raised when the ScrollBar is scrolled.</td></tr>
<tr><td>ValueChanged</td><td>Raised when the value of the ScrollBar changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

