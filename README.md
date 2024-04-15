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

# Changing the colors
The styles are in wwwroot/css/site.css
```css
html {
  font-size: 14px;
}

@media (min-width: 768px) {
  html {
    font-size: 16px;
  }
}

.btn:focus, .btn:active:focus, .btn-link.nav-link:focus, .form-control:focus, .form-check-input:focus {
  box-shadow: 0 0 0 0.1rem white, 0 0 0 0.25rem #258cfb;
}

html {
  position: relative;
  min-height: 100%;
}

body {
  margin-bottom: 60px;
}
```
The stlying uses bootstrap (wwwroot/lib/bootstrap/dist/css)

Scott has a great video here: https://www.youtube.com/watch?v=9lJF47kFRcU

For a crude hack you could edit these styles directly
```csss
body {
  margin-bottom: 60px;
  background-color: black;
  color:#FFF;
}
```