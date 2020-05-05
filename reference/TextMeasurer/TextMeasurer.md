---

title: TextMeasurer Class

---

# TextMeasurer Class

Provides functions for measuring text and related operations.

```csharp
public static class TextMeasurer 
```

## Fields

<table>
<tr><td>MaxSize</td><td>Represents the maximum size of a text area.</td></tr>
</table>

## Methods

<table>
<tr><td>FindNextSeparator (String, Int32, Boolean)</td><td>Finds the next word separator in the specified text.</td></tr>
<tr><td>GetCursorLocation (String, Rectangle, SKTypeface, Int32, Size, ContentAlignment, Int32, Nullable`1)</td><td></td></tr>
<tr><td>GetCursorLocation (TextBlock, Point, Int32, Int32)</td><td>Gets the cursor location at the specified code point.</td></tr>
<tr><td>GetMaxCaretIndex (String)</td><td>Gets the maximum carent index of the specified text.</td></tr>
<tr><td>HitTest (String, Rectangle, SKTypeface, Int32, Size, ContentAlignment, Point, Nullable`1)</td><td></td></tr>
<tr><td>IsWordSeparator (Char)</td><td>Determines if the specified character is a word separator.</td></tr>
<tr><td>MeasureText (String, Control)</td><td>Measures the specified text using font characteristics from the provided control.</td></tr>
<tr><td>MeasureText (String, Control, Size)</td><td>Measures the specified text using font characteristics from the provided control.</td></tr>
<tr><td>MeasureText (String, SKTypeface, Int32)</td><td>Measures the specified text using the provided font characteristics.</td></tr>
<tr><td>MeasureText (String, SKTypeface, Int32, Size)</td><td>Measures the specified text using the provided font characteristics.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

