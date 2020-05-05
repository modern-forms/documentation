---

title: ScrollEventArgs Class

---

# ScrollEventArgs Class

Provides data for the ScrollBar.Scroll event.

```csharp
public class ScrollEventArgs : EventArgs 
```

## Constructors

<table>
<tr><td>ScrollEventArgs (ScrollEventType, Int32)</td><td>Initializes a new instance of the ScrollEventArgs class.</td></tr>
<tr><td>ScrollEventArgs (ScrollEventType, Int32, ScrollOrientation)</td><td>Initializes a new instance of the ScrollEventArgs class.</td></tr>
<tr><td>ScrollEventArgs (ScrollEventType, Int32, Int32)</td><td>Initializes a new instance of the ScrollEventArgs class.</td></tr>
<tr><td>ScrollEventArgs (ScrollEventType, Int32, Int32, ScrollOrientation)</td><td>Initializes a new instance of the ScrollEventArgs class.</td></tr>
</table>

## Properties

<table>
<tr><td>NewValue</td><td>Specifies the new location of the scroll box within the scroll bar.</td></tr>
<tr><td>OldValue</td><td>Specifies the last position  within the scroll bar.</td></tr>
<tr><td>ScrollOrientation</td><td>Specifies the type of scroll event that occurred.</td></tr>
<tr><td>Type</td><td>Specifies the type of scroll event that occurred.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

