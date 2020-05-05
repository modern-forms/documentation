---

title: ListView Class

---

# ListView Class

Represents a ListView control.
            Note the ListView control has not been fully developed, and probably does not contain enough functionality to be useful yet.

```csharp
public class ListView : Control 
```

## Constructors

<table>
<tr><td>ListView ()</td><td>Initializes a new instance of the ListView class.</td></tr>
</table>

## Fields

<table>
<tr><td>DefaultStyle</td><td></td></tr>
</table>

## Properties

<table>
<tr><td>DefaultPadding</td><td>Gets the default padding of the control.</td></tr>
<tr><td>DefaultSize</td><td>Gets the default size of the control.</td></tr>
<tr><td>Items</td><td>Gets the collection of items contained by this ListView.</td></tr>
<tr><td>SelectedItem</td><td>Gets or sets the currently selected item, if any. If there are multiple selected items, the first selected item will be returned.</td></tr>
<tr><td>Style</td><td>Gets the ControlStyle properties for this instance of the Control.</td></tr>
</table>

## Methods

<table>
<tr><td>OnClick (MouseEventArgs)</td><td>Raises the OnClick event.</td></tr>
<tr><td>OnDoubleClick (MouseEventArgs)</td><td>Raises the DoubleClick event.</td></tr>
<tr><td>OnPaint (PaintEventArgs)</td><td>Paints the control.</td></tr>
</table>

## Events

<table>
<tr><td>ItemDoubleClicked</td><td>Raised when a list view item is double-clicked.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

