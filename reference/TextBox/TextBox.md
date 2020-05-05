---

title: TextBox Class

---

# TextBox Class

Represents a TextBox control.

```csharp
public class TextBox : ScrollControl 
```

## Constructors

<table>
<tr><td>TextBox ()</td><td>Initializes a new instance of the TextBox class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>DefaultPadding</td><td>Gets the default padding of the control.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>MaxLength</td><td>Gets or sets a value indicating the maximum length of text the TextBox can hold.</td></tr>
<tr><td>MultiLine</td><td>Gets or sets a value indicating if the TextBox supports multiple lines of text.</td></tr>
<tr><td>PasswordCharacter</td><td>Gets or sets a character to display instead of the actual text.</td></tr>
<tr><td>Placeholder</td><td>Gets or sets text to display if the TextBox contains no text.</td></tr>
<tr><td>ReadOnly</td><td>Gets or sets a value indicating if the text can be edited.</td></tr>
<tr><td>SelectionEnd</td><td>Gets or sets a value indicating the end of the TextBox's selected text.</td></tr>
<tr><td>SelectionStart</td><td>Gets or sets a value indicating the start of the TextBox's selected text.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
<tr><td>Text</td><td>Gets or sets the text of the control.</td></tr>
</table>

## Methods

<table>
<tr><td>Copy ()</td><td>Copies the selected text of the TextBox to the clipboard.</td></tr>
<tr><td>Cut ()</td><td>Copies the selected text of the TextBox to the clipboard and removes it from the TextBox.</td></tr>
<tr><td>OnDeselected (EventArgs)</td><td>Called when the control is deselected.</td></tr>
<tr><td>OnEnabledChanged (EventArgs)</td><td>Raises the EnabledChanged event.</td></tr>
<tr><td>OnKeyDown (KeyEventArgs)</td><td>Raises the KeyDown event.</td></tr>
<tr><td>OnKeyPress (KeyPressEventArgs)</td><td>Raises the KeyPress event.</td></tr>
<tr><td>OnMouseDown (MouseEventArgs)</td><td>Raises the MouseDown event.</td></tr>
<tr><td>OnMouseMove (MouseEventArgs)</td><td>Raises the MouseMove event.</td></tr>
<tr><td>OnMouseUp (MouseEventArgs)</td><td>Raises the MouseUp event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnSizeChanged (EventArgs)</td><td>Raises the SizeChanged event.</td></tr>
<tr><td>Paste ()</td><td>Inserts any text on the clipboard into the TextBox.</td></tr>
<tr><td>ScrollToCaret ()</td><td>Scrolls the TextBox so that the caret is visible.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

