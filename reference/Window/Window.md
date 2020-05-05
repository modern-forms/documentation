---

title: Window Class

---

# Window Class

Represents the base class for windows, like Form and PopupWindow

```csharp
public abstract class Window 
```

## Fields

<table>
<tr><td>DefaultStyle</td><td>Gets the default style for all windows of this type.</td></tr>
</table>

## Properties

<table>
<tr><td>Controls</td><td>Gets the collection of controls contained by the window.</td></tr>
<tr><td>CurrentStyle</td><td>Gets the current style of this window instance.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the window.</td></tr>
<tr><td>DisplayRectangle</td><td>Gets the unscaled bounds of the form not including borders.</td></tr>
<tr><td>Location</td><td>Gets or sets the unscaled location of the control.</td></tr>
<tr><td>Resizeable</td><td>Gets or sets whether the window is resizable.</td></tr>
<tr><td>ScaledDisplayRectangle</td><td>Gets the scaled bounds of the form not including borders.</td></tr>
<tr><td>ScaledSize</td><td>Gets or sets the scaled size of the window.</td></tr>
<tr><td>Scaling</td><td>Gets the current scale factor of the window.</td></tr>
<tr><td>Size</td><td>Gets or sets the unscaled size of the window.</td></tr>
<tr><td>StartPosition</td><td>Gets or sets the startup location of the window.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the window.</td></tr>
<tr><td>Visible</td><td>Gets or sets whether the window is displayed to the user.</td></tr>
</table>

## Methods

<table>
<tr><td>BeginMoveDrag ()</td><td>Begins dragging the window to move it.</td></tr>
<tr><td>Close ()</td><td>Closes and destroys the window.</td></tr>
<tr><td>Hide ()</td><td>Hides the window without destroying it.</td></tr>
<tr><td>Invalidate ()</td><td>Marks the entire window as needing to be redrawn.</td></tr>
<tr><td>Invalidate (Rectangle)</td><td>Marks the specified portion of the window as needing to be redrawn.</td></tr>
<tr><td>OnShown (EventArgs)</td><td>Raises the Shown event.</td></tr>
<tr><td>PointToScreen (Point)</td><td>Converts a point from window coordinates to monitor coordinates.</td></tr>
<tr><td>Show ()</td><td>Displays the window to the user.</td></tr>
</table>

## Events

<table>
<tr><td>Closed</td><td>Raised when the window is closed.</td></tr>
<tr><td>Deactivated</td><td>Raised when the window is deactivated.</td></tr>
<tr><td>Shown</td><td>Raised when the window is shown.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

