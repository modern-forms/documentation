---

title: Application Class

---

# Application Class

Provides static methods and properties to manage an application, such as methods to start and stop an application.

```csharp
public static class Application 
```

## Methods

<table>
<tr><td>Exit ()</td><td>Exits the application.</td></tr>
<tr><td>Run (Form)</td><td>Begins running a standard application message loop on the current thread, and makes the specified form visible.</td></tr>
<tr><td>Run (ICloseable)</td><td>Runs the application's main loop until the  is closed.</td></tr>
<tr><td>RunOnUIThread (Action)</td><td>Performs the desired Action on the UI thread.</td></tr>
</table>

## Events

<table>
<tr><td>OnExit</td><td>Raised when the application is exiting.</td></tr>
</table>

<!-- Only change content below this line, anything above this line will be lost when regenerated. -->

## Examples

The most common use of this class is to start running a Modern.Forms application using
a specified Form.

```
public static void Main (string[] args)
{
    var form = new Form ();

    form.Controls.Add (new Button ());

    Application.Run (form);
}
```

This will display the `Form` to the user.  When the `Form` is closed, the application
will automatically terminate.

## Remarks

