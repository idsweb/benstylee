# benstylee
## This site was set up to help my son style his webapp!

# Changing the tilte
The title of the site is set in ViewData in the cshtml file for index (index.cshtml)
```csharp
@page
@model IndexModel
@{
    ViewData["Title"] = "Home page";
}

<div class="text-center">
    <h1 class="display-4">Welcome</h1>
    <p>Learn about <a href="https://docs.microsoft.com/aspnet/core">building Web apps with ASP.NET Core</a>.</p>
</div>
```
To change the title of the site change the title property. This will update the tilte bar in IE.
# Changing the H1
You can change the H1 of the page from Welcome to the message of your choice by editing the markup above.

