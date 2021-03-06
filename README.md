Geta Tags for EPiServer CMS
====
## What is Geta Tags?

Geta Tags is library that adds tagging functionality to EPiServer Pages.

## How to get started?

Start by installing NuGet package (use [EPiServer NuGet](http://nuget.episerver.com/)):

    Install-Package Geta.Tags

The latest version 1.0.0 is compiled for .NET 4.0 and EPiServer 7.5. 
Geta Tags library uses [tag-it](https://github.com/aehlke/tag-it) jQuery UI plugin for selecting tags.
To add Tags as a new property to your page types you need to use the UIHint attribute like in this example:

```csharp
[UIHint("Tags")]
public virtual string Tags { get; set; }
```

For an introduction see: [Tags for EPiServer CMS] (http://www.frederikvig.com/2011/07/tags-for-episerver-cms/) and [Tags version 0.2 released for EPiServer CMS] (http://www.frederikvig.com/2011/09/tags-version-0-2-released-for-episerver-cms/).
