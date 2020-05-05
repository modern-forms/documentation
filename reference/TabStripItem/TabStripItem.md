---

title: TabStripItem Class

---

# TabStripItem Class

Represents a TabStripItem.

```csharp
public class TabStripItem : ILayoutable 
```

## Constructors

<table>
<tr><td>TabStripItem (String)</td><td>Initializes a new instance of the TabStripItem class.</td></tr>
</table>

## Properties

<table>
<tr><td>Bounds</td><td>Gets the current bounding box of the tab.</td></tr>
<tr><td>Enabled</td><td>Gets or sets a value indicating whether the tab is enabled.</td></tr>
<tr><td>Hovered</td><td>Gets a value indicating if the tab currently has the mouse hovered over it.</td></tr>
<tr><td>Margin</td><td>Gets or sets the amount of space to leave between this tab and other elements.</td></tr>
<tr><td>Padding</td><td>Gets or sets the amount of space to leave between the text and the border of the tab.</td></tr>
<tr><td>Parent</td><td>Gets the TabStrip this tab is currently a part of.</td></tr>
<tr><td>Selected</td><td>Gets a value indicating if the tab is currently the selected tab.</td></tr>
<tr><td>Tag</td><td>Gets or sets an object with additional user data about this tab.</td></tr>
<tr><td>Text</td><td>Gets or sets the text displayed on the tab.</td></tr>
</table>

## Methods

<table>
<tr><td>GetPreferredSize (Size)</td><td>Gets the preferred size of the tab.</td></tr>
<tr><td>SetBounds (Int32, Int32, Int32, Int32, BoundsSpecified)</td><td>Sets the bounding box of the tab. This is internal API and should not be called.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

