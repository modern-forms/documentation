---

title: Form Class

---

# Form Class

Represents a top-level window to display to the user.

```csharp
public class Form : Window, ICloseable 
```

## Constructors

<table>
<tr><td>Form ()</td><td>Initializes a new instance of the Form class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td>Gets the default style for all forms.</td></tr>
</table>

## Properties

<table>
<tr><td>AllowMaximize</td><td>Gets or sets whether the form can be maximized.</td></tr>
<tr><td>AllowMinimize</td><td>Gets or sets whether the form can be minimized.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the window.</td></tr>
<tr><td>Image</td><td>Gets or sets the icon for the form.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the window.</td></tr>
<tr><td>Text</td><td>Gets or sets the text for the form title bar.</td></tr>
<tr><td>TitleBar</td><td>Gets the title bar for the form.</td></tr>
<tr><td>UseSystemDecorations</td><td>Gets or sets whether the form should use the operating system's title bar and decorations,
            or use managed decorations.  The default is false.  This must be changed before the form
            is shown for the first time.</td></tr>
<tr><td>WindowState</td><td>Gets or sets the state of the form (normal/minimized/maximized).</td></tr>
</table>

## Methods

<table>
<tr><td>GetNextControl (Control, Boolean)</td><td>Gets the next control in tab order.</td></tr>
<tr><td>ShowDialog (Form)</td><td>Displays the window to the user modally, preventing interaction with other windows until closed.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

