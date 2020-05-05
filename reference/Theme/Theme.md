---

title: Theme Class

---

# Theme Class

Provides a repository of color resources.

```csharp
public static class Theme 
```

## Properties

<table>
<tr><td>BorderGray</td><td>A darker gray used as the default control border color.</td></tr>
<tr><td>DarkNeutralGray</td><td>A darker gray generally used for showing an item is currently pressed.</td></tr>
<tr><td>DisabledTextColor</td><td>The color used for disabled text.</td></tr>
<tr><td>FontSize</td><td>The default font size used by control.</td></tr>
<tr><td>FormBackgroundColor</td><td>The background color of a form.</td></tr>
<tr><td>FormCloseHighlightColor</td><td>The color used to draw a form's close button when highlighted.</td></tr>
<tr><td>HighlightColor</td><td>The color used for highlighted elements, like hovered tabs or buttons.</td></tr>
<tr><td>ItemFontSize</td><td>A smaller font size generally used for lists of items.</td></tr>
<tr><td>ItemHighlightColor</td><td>The color used for a highlighted item's background.</td></tr>
<tr><td>ItemSelectedColor</td><td>The color used for a selected item's background.</td></tr>
<tr><td>LightNeutralGray</td><td>A lighter gray used primarily used as the background of list items.</td></tr>
<tr><td>LightTextColor</td><td>A lighter text color, often used when an element is selected with a darker background.</td></tr>
<tr><td>NeutralGray</td><td>A neutral gray used as the default background of controls.</td></tr>
<tr><td>PrimaryColor</td><td>The primary color for elements such as the title bar, tabs, checkboxes and radio button glyph.</td></tr>
<tr><td>PrimaryTextColor</td><td>The primary text color.</td></tr>
<tr><td>UIFont</td><td>The default font used by controls.</td></tr>
</table>

## Methods

<table>
<tr><td>BeginUpdate ()</td><td>Pause raising ThemeChanged for better performance if changing many Theme elements.
            Resume with EndUpdate ().</td></tr>
<tr><td>EndUpdate ()</td><td>Resume raising the ThemeChanged event after pausing with BeginUpdate ().</td></tr>
</table>

## Events

<table>
<tr><td>ThemeChanged</td><td>Raised when a theme color is changed. Controls listen
            for this event to know when to repaint themselves.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

