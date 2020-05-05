---

title: RibbonRenderer Class

---

# RibbonRenderer Class

Represents a class that can render a Ribbon.

```csharp
public class RibbonRenderer : Renderer<Ribbon> 
```

## Constructors

<table>
<tr><td>RibbonRenderer ()</td><td></td></tr>
</table>

## Fields

<table>
<tr><td>IMAGE_SIZE</td><td>Size of a ribbon item image.</td></tr>
<tr><td>MINIMUM_ITEM_SIZE</td><td>Minimum size of a ribbon item.</td></tr>
</table>

## Methods

<table>
<tr><td>GetPreferredItemSize (Ribbon, MenuItem, Size)</td><td>Gets the preferred size of a MenuItem.</td></tr>
<tr><td>GetPreferredSeparatorItemSize (Ribbon, MenuSeparatorItem, Size)</td><td>Gets the preferred size of a MenuSeparatorItem.</td></tr>
<tr><td>LayoutTabPage (RibbonTabPage)</td><td>Performs a layout of the tab page's items.</td></tr>
<tr><td>Render (Ribbon, PaintEventArgs)</td><td>Renders the control.</td></tr>
<tr><td>RenderItem (Ribbon, RibbonTabPage, RibbonItemGroup, MenuItem, PaintEventArgs)</td><td>Renders a MenuItem.</td></tr>
<tr><td>RenderItemGroup (Ribbon, RibbonTabPage, RibbonItemGroup, PaintEventArgs)</td><td>Renders a RibbonItemGroup.</td></tr>
<tr><td>RenderMenuSeparatorItem (Ribbon, RibbonTabPage, RibbonItemGroup, MenuSeparatorItem, PaintEventArgs)</td><td>Renders a MenuSeparatorItem.</td></tr>
<tr><td>RenderTabPage (Ribbon, RibbonTabPage, PaintEventArgs)</td><td>Renders a RibbonTabPage.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

