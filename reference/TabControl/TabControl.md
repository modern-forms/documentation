---

title: TabControl Class

---

# TabControl Class

Represents a TabControl control.

```csharp
public class TabControl : Control 
```

## Constructors

<table>
<tr><td>TabControl ()</td><td>Initializes a new instance of the TabControl class.</td></tr>
</table>

## Properties

<table>
<tr><td>SelectedIndex</td><td>Gets or sets the index of the currently selected tab page. This value will be -1 if there is not a selected tab page;</td></tr>
<tr><td>SelectedTabPage</td><td>Gets or sets the currently selected tab page.</td></tr>
<tr><td>TabPages</td><td>Gets the collection of tabs contained by this TabControl.</td></tr>
</table>

## Methods

<table>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
<tr><td>OnSelectedIndexChanged (EventArgs)</td><td>Raises the SelectedIndexChanged event.</td></tr>
</table>

## Events

<table>
<tr><td>SelectedIndexChanged</td><td>Raised when the value of the SelectedIndex property changes.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

