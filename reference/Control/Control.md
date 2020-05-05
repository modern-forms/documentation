---

title: Control Class

---

# Control Class

Represents the base class for all Controls.

```csharp
public class Control : ILayoutable, IDisposable 
```

## Constructors

<table>
<tr><td>Control ()</td><td>Initializes a new instance of the Control class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td>Gets the default style for all controls of this type.</td></tr>
<tr><td>DefaultStyleHover</td><td>Gets the default style for all controls of this type when the user is hovering over it.</td></tr>
</table>

## Properties

<table>
<tr><td>Anchor</td><td>Gets or sets a value indicating which sides of the control are anchored when its parent resizes.</td></tr>
<tr><td>AutoSize</td><td>Gets a value indicating if this control's size can be changed automatically.</td></tr>
<tr><td>Bottom</td><td>Gets the unscaled bottom location of the control.</td></tr>
<tr><td>Bounds</td><td>Gets or sets the unscaled bounds of the control.</td></tr>
<tr><td>CanSelect</td><td>Gets a value indicating the control can receive focus.</td></tr>
<tr><td>Capture</td><td>Gets or sets a value indicating the control is currently getting system mouse events.</td></tr>
<tr><td>ClientRectangle</td><td>Gets the scaled bounds of the control's canvas minus any borders.</td></tr>
<tr><td>ClientSize</td><td>Gets the scaled size of the control.</td></tr>
<tr><td>ContextMenu</td><td>Gets or sets the context menu that will be shown for the control.</td></tr>
<tr><td>Controls</td><td>Gets the collection of controls contained by the control.</td></tr>
<tr><td>CurrentStyle</td><td>Gets the current style of this control instance.</td></tr>
<tr><td>Cursor</td><td>Gets or sets the mouse cursor to be shown when the mouse is over the control.</td></tr>
<tr><td>DefaultCursor</td><td>Gets the default cursor.</td></tr>
<tr><td>DefaultMargin</td><td>Gets the default margin of the control.</td></tr>
<tr><td>DefaultPadding</td><td>Gets the default padding of the control.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>DeviceDpi</td><td>Gets the DPI of the current monitor.</td></tr>
<tr><td>DisplayRectangle</td><td>Gets the scaled bounds of the displayed control.</td></tr>
<tr><td>Dock</td><td>Gets or sets which side the control is docked to.</td></tr>
<tr><td>Enabled</td><td>Gets or sets whether the control can be interacted with.</td></tr>
<tr><td>Height</td><td>Gets or sets the unscaled height of the control.</td></tr>
<tr><td>Left</td><td>Gets or sets the unscaled left boundary of the control.</td></tr>
<tr><td>Location</td><td>Gets or sets the unscaled location of the control.</td></tr>
<tr><td>Margin</td><td>Gets or sets how much space there should be between the control and other controls.</td></tr>
<tr><td>Name</td><td>Gets or sets a user specified name for the control.</td></tr>
<tr><td>PaddedClientRectangle</td><td>The scaled control canvas minus any borders and Padding.</td></tr>
<tr><td>Padding</td><td>Gets or sets the amount of space there should be between the control bounds and the control contents.</td></tr>
<tr><td>Parent</td><td>Gets or sets the control that contains this control.</td></tr>
<tr><td>PreferredSize</td><td>Gets the size the control would prefer to be.</td></tr>
<tr><td>Right</td><td>Gets the unscaled right boundary of the control.</td></tr>
<tr><td>ScaledBounds</td><td>Gets the scaled bounds of the control.</td></tr>
<tr><td>ScaledHeight</td><td>Gets the scaled height of the control.</td></tr>
<tr><td>ScaledLeft</td><td>Gets the scaled left of the control.</td></tr>
<tr><td>ScaledSize</td><td>Gets the scaled size of the control.</td></tr>
<tr><td>ScaledTop</td><td>Gets the scaled top of the control.</td></tr>
<tr><td>ScaledWidth</td><td>Gets the scaled width of the control.</td></tr>
<tr><td>ScaleFactor</td><td>Gets the current scale factor of the control.</td></tr>
<tr><td>Scaling</td><td>Gets the current scale factor of the form.</td></tr>
<tr><td>Selected</td><td>Gets a value indicating the control has focus.</td></tr>
<tr><td>Size</td><td>Gets or sets the unscaled size of the control.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>StyleHover</td><td>Gets the ControlStyle properties for this instance of the Control when the user is hovering over it.</td></tr>
<tr><td>TabIndex</td><td>Gets or sets a value indicating the order the control is selected when pressing tab.</td></tr>
<tr><td>TabStop</td><td>Gets or sets whether the control is selectable via pressing tab.</td></tr>
<tr><td>Tag</td><td>Gets or sets user defined data.</td></tr>
<tr><td>Text</td><td>Gets or sets the text of the control.</td></tr>
<tr><td>Top</td><td>Gets or sets the unscaled top boundary of the control.</td></tr>
<tr><td>Visible</td><td>Gets or sets whether the control is displayed to the user.</td></tr>
<tr><td>Width</td><td>Gets or sets the unscaled width of the control.</td></tr>
</table>

## Methods

<table>
<tr><td>Contains (Control)</td><td>Gets a value indicating if the specified control is parented to this control or any of its children.</td></tr>
<tr><td>Dispose (Boolean)</td><td>Disposes unmanaged resources used by the control.</td></tr>
<tr><td>Dispose ()</td><td>Disposes unmanaged resources used by the control. This code added to correctly implement the disposable pattern.</td></tr>
<tr><td>Finalize ()</td><td>Destroys the control.</td></tr>
<tr><td>FindForm ()</td><td>Gets the Form that the control is parented to.</td></tr>
<tr><td>GetNextControl (Control, Boolean)</td><td>Gets the next control in tab order.</td></tr>
<tr><td>GetPreferredSize (Size)</td><td>Gets the size the control would prefer to be.</td></tr>
<tr><td>GetScaledBounds (Rectangle, SizeF, BoundsSpecified)</td><td>Scales bounds by a specified factor.</td></tr>
<tr><td>Invalidate ()</td><td>Marks the entire control as needing to be redrawn.</td></tr>
<tr><td>Invalidate (Rectangle)</td><td>Marks the specified portion of the control as needing to be redrawn.</td></tr>
<tr><td>LogicalToDeviceUnits (Int32)</td><td>Converts an unscaled value to a scaled value.</td></tr>
<tr><td>LogicalToDeviceUnits (Padding)</td><td>Converts an unscaled Padding to a scaled Padding.</td></tr>
<tr><td>LogicalToDeviceUnits (Size)</td><td>Converts an unscaled Size to a scaled Size.</td></tr>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnCursorChanged (EventArgs)</td><td>Raises the CursorChanged event.</td></tr>
<tr><td>OnDeselected (EventArgs)</td><td>Called when the control is deselected.</td></tr>
<tr><td>OnDockChanged (EventArgs)</td><td>Raises the DockChanged event.</td></tr>
<tr><td>OnDoubleClick (MouseEventArgs)</td><td>Raises the DoubleClick event.</td></tr>
<tr><td>OnEnabledChanged (EventArgs)</td><td>Raises the EnabledChanged event.</td></tr>
<tr><td>OnKeyDown (KeyEventArgs)</td><td>Raises the KeyDown event.</td></tr>
<tr><td>OnKeyPress (KeyPressEventArgs)</td><td>Raises the KeyPress event.</td></tr>
<tr><td>OnKeyUp (KeyEventArgs)</td><td>Raises the KeyUp event.</td></tr>
<tr><td>OnLayout (LayoutEventArgs)</td><td>Raises the Layout event.</td></tr>
<tr><td>OnLocationChanged (EventArgs)</td><td>Raises the LocationChanged event.</td></tr>
<tr><td>OnMarginChanged (EventArgs)</td><td>Raises the MarginChanged event.</td></tr>
<tr><td>OnMouseDown (MouseEventArgs)</td><td>Raises the MouseDown event.</td></tr>
<tr><td>OnMouseEnter (MouseEventArgs)</td><td>Raises the MouseEnter event.</td></tr>
<tr><td>OnMouseLeave (EventArgs)</td><td>Raises the MouseLeave event.</td></tr>
<tr><td>OnMouseMove (MouseEventArgs)</td><td>Raises the MouseMove event.</td></tr>
<tr><td>OnMouseUp (MouseEventArgs)</td><td>Raises the MouseUp event.</td></tr>
<tr><td>OnMouseWheel (MouseEventArgs)</td><td>Raises the MouseWheel event.</td></tr>
<tr><td>OnPaddingChanged (EventArgs)</td><td>Raises the PaddingChanged event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnPaintBackground (PaintEventArgs)</td><td>Paints the control's background.</td></tr>
<tr><td>OnParentVisibleChanged (EventArgs)</td><td>Called when the Parent's Visible property is changed.</td></tr>
<tr><td>OnSizeChanged (EventArgs)</td><td>Raises the SizeChanged event.</td></tr>
<tr><td>OnTabIndexChanged (EventArgs)</td><td>Raises the TabIndexChanged event.</td></tr>
<tr><td>OnTabStopChanged (EventArgs)</td><td>Raises the TabStopChanged event.</td></tr>
<tr><td>OnTextChanged (EventArgs)</td><td>Raises the TextChanged event.</td></tr>
<tr><td>OnVisibleChanged (EventArgs)</td><td>Raises the VisibleChanged event.</td></tr>
<tr><td>PerformLayout ()</td><td>Triggers the control to layout its children.</td></tr>
<tr><td>PerformLayout (Control, String)</td><td>Triggers the control to layout its children.</td></tr>
<tr><td>PointToScreen (Point)</td><td>Converts a point from control coordinates to monitor coordinates.</td></tr>
<tr><td>ResumeLayout (Boolean)</td><td>Notifies the control to result performing layouts originally suspended with SuspendLayout.</td></tr>
<tr><td>Scale (SizeF)</td><td>Scales the control by the specified factor.</td></tr>
<tr><td>ScaleCore (Single, Single)</td><td>Scales the control by the specified factor.</td></tr>
<tr><td>Select ()</td><td>Gives the control focus.</td></tr>
<tr><td>SelectNextControl (Control, Boolean, Boolean, Boolean, Boolean)</td><td>Moves focus to the next control.</td></tr>
<tr><td>SetBounds (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>Sets the unscaled bounds of the control.</td></tr>
<tr><td>SetBoundsCore (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>A version of SetBounds that can be overridden by subclasses.</td></tr>
<tr><td>SetControlBehavior (ControlBehaviors, Boolean)</td><td>Sets behavior flags.</td></tr>
<tr><td>SuspendLayout ()</td><td>Pauses performing layouts until ResumeLayout is called.</td></tr>
</table>

## Events

<table>
<tr><td>Click</td><td>Raised when this control is clicked.</td></tr>
<tr><td>CursorChanged</td><td>Raised when the Cursor property is changed.</td></tr>
<tr><td>DockChanged</td><td>Raised when the Dock property is changed.</td></tr>
<tr><td>DoubleClick</td><td>Raised when this control is double-clicked.</td></tr>
<tr><td>EnabledChanged</td><td>Raised when the Enabled property is changed.</td></tr>
<tr><td>KeyDown</td><td>Raised when the user presses down a key.</td></tr>
<tr><td>KeyPress</td><td>Raised when the user presses a key.</td></tr>
<tr><td>KeyUp</td><td>Raised when the user releases a key.</td></tr>
<tr><td>Layout</td><td>Raised when the control performs a layout.</td></tr>
<tr><td>LocationChanged</td><td>Raised when the Location property is changed.</td></tr>
<tr><td>MarginChanged</td><td>Raised when the Margin property is changed.</td></tr>
<tr><td>MouseDown</td><td>Raised when a mouse button is pressed.</td></tr>
<tr><td>MouseEnter</td><td>Raised when the mouse cursor enters the control.</td></tr>
<tr><td>MouseLeave</td><td>Raised when the mouse cursor leaves the control.</td></tr>
<tr><td>MouseMove</td><td>Raised when the mouse cursor is moved within the control.</td></tr>
<tr><td>MouseUp</td><td>Raised when a mouse button ir released.</td></tr>
<tr><td>MouseWheel</td><td>Raised when a mouse wheel is rotated.</td></tr>
<tr><td>PaddingChanged</td><td>Raised when the Padding property is changed.</td></tr>
<tr><td>SizeChanged</td><td>Raised when the Size property is changed.</td></tr>
<tr><td>TabIndexChanged</td><td>Raised when the TabIndex property is changed.</td></tr>
<tr><td>TabStopChanged</td><td>Raised when the TabStop property is changed.</td></tr>
<tr><td>TextChanged</td><td>Raised when the Text property is changed.</td></tr>
<tr><td>VisibleChanged</td><td>Raised when the Visisble property is changed.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

