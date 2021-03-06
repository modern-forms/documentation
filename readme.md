# Documentation for Modern.Forms

This repository contains the source for [Modern.Forms](https://github.com/modern-forms/Modern.Forms) documentation available [here](tbd).

### Guides

"Guide" documentation are articles or tutorials designed to teach how to use something.
For example, the [Getting Started](guides/getting-started.md) guide shows how to create
a new Modern.Forms project.

This documentation lives in the `guides` directory.

To create a new guide simply add it to the `guides` directory.  Do not add it to the `toc.xml`
file as this is autogenerated based on the content found.

### Reference

"Reference" documentation details what the Modern.Forms API is and how to use it.  This
documentation is generated from the Modern.Forms source and optionally augmented with
additional descriptions and samples in this repository.

This documentation lives in the `reference` directory.

The `Examples` and `Remarks` sections of API reference pages can be modified in this 
repository.  Changes to any other section will be overwritten the next time documentation
is generated.

An example of augmented documentation can be see for the [Application class](https://github.com/modern-forms/documentation/blob/master/reference/Application/Application.md).

### Cache

The documentation site caches content from this repository for 2 hours, so it may take a little
time before committed changes are reflected there.

### License

Documentation is both original and ported from the Microsoft System.Windows.Forms [documentation](https://docs.microsoft.com/en-us/dotnet/api/system.windows.forms?view=netcore-3.1).

It is licensed as [CC-Attribution 4.0 International](license.txt).

It is permissable to incorporate Microsoft documentation into this repository.