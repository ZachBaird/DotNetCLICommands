# Important .NET Core CLI commands to keep tabs on.

Note that these commands assume you are running at least .NET Core 3.

* To publish a .NET Core app as a self-contained, single-file executable:

```cs
dotnet publish -r win-x64 -c Release /p:PublishSingleFile=true
```

* To install the Nyancat tool:

```cs
dotnet tool install --global nyancat --version 1.4.0
```
