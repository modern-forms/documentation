---

title: PictureBoxSizeMode Enum

---

# PictureBoxSizeMode Enum

Specifies how an image is positioned within a .

```csharp
public enum PictureBoxSizeMode 
```

## Fields

<table>
<tr><td>AutoSize</td><td>The  is sized to fit the
             size of the image that is displayed.</td></tr>
<tr><td>CenterImage</td><td>The image is displayed in the center if the
             is larger than the
             image. If the image is larger than the ,
             the center of the picture is placed in the center of the
             and the outside edges are
             clipped.</td></tr>
<tr><td>Normal</td><td>The image is placed in the top-left corner of the
            . The image is clipped
             if the  is to small.</td></tr>
<tr><td>StretchImage</td><td>The image within the  is stretched or shrunk to fit the
             current size of the .</td></tr>
<tr><td>Zoom</td><td>The size of image is increased or decresed maintaining the aspect ratio.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

## Remarks

