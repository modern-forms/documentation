---

title: AutoSizeMode Enum

---

# AutoSizeMode Enum

Specifies how the control will behave when its AutoSize property is enabled

```csharp
public enum AutoSizeMode 
```

## Fields

<table>
<tr><td>GrowAndShrink</td><td>The same behavior as you get for controls with AutoSize and no AutoSizeMode
             property. The control will grow or shrink to encompass the contents (e.g.
             text for a Button, child controls for a container). The MinimumSize and
             MaximumSize are followed, but the current value of the Size property is
             ignored.</td></tr>
<tr><td>GrowOnly</td><td>The control will grow as much as it needs to encompass its contents (e.g.
             text for a button, child controls for a container), but will not shrink
             smaller than its Size, whichever is larger.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

