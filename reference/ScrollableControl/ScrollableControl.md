---

title: ScrollableControl Class

---

# ScrollableControl Class

Represents a ScrollableControl control.

```csharp
public class ScrollableControl : Control 
```

## Constructors

<table>
<tr><td>ScrollableControl ()</td><td>Initializes a new instance of the ScrollableControl class.</td></tr>
</table>

## Properties

<table>
<tr><td>AutoScroll</td><td>Gets or sets a value indicating the user can scroll to controls beyond the ScrollableControl's bounds.</td></tr>
<tr><td>HorizontalScrollProperties</td><td>Provides access to the properties of the horizontal scrollbar.</td></tr>
<tr><td>VerticalScrollProperties</td><td>Provides access to the properties of the vertical scrollbar.</td></tr>
</table>

## Methods

<table>
<tr><td>AdjustFormScrollbars (Boolean)</td><td>Adjusts the scrollbars based on the currently contained controls.</td></tr>
<tr><td>OnLayout (LayoutEventArgs)</td><td>Raises the Layout event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnScroll (ScrollEventArgs)</td><td>Raises the Scroll event.</td></tr>
</table>

## Events

<table>
<tr><td>Scroll</td><td>Raised when the ScrollableControl is scrolled.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

