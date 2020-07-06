# Important .NET Core CLI commands to keep tabs on.

Note that these commands assume you are running at least .NET Core 3.

* To publish a .NET Core app as a self-contained, single-file executable:

```cs
dotnet publish -r win-x64 -c Release /p:PublishSingleFile=true
```

* To install the current preview version of client-side Blazor:

```cs
dotnet new --install Microsoft.AspNetCore.Blazor.Templates::3.0.0-preview9.19465.2
```

* To install the Nyancat too:

```cs
dotnet tool install --global nyancat --version 1.4.0
```
