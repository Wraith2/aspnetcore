# Error Page

This folder is shared among multiple projects. The `ErrorPage.Designer.cs` and `ErrorPageModel.cs` files are used to render this view. The `ErrorPage.Designer.cs` file is generated by rendering `src/Views/ErrorPage.cshtml` using the [RazorPageGenerator](https://github.com/dotnet/aspnetcore-tooling/tree/master/src/Razor/src/RazorPageGenerator) tool.

## Making changes to ErrorPage.cshtml

1. Clone dotnet/aspnetcore-tooling
1. Run `./build.cmd` in **that repo**
1. Edit the file
1. Run the `GeneratePage` script, passing in the path to the `dotnet/aspnetcore-tooling` repo root.

```
.\GeneratePage -ToolingRepoPath C:\Code\aspnet\AspNetCore-Tooling
```
