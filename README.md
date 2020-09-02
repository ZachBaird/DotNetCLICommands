# Important .NET Core CLI commands to keep tabs on.

Note that these commands assume you are running at least .NET Core 3.

* To publish a .NET Core app as a self-contained, single-file executable:

```cs
dotnet publish -r win-x64 -c Release /p:PublishSingleFile=true
```

* To install Bolero.Templates for F# WASM on top of Blazor

```cs
dotnet new -i Bolero.Templates
```

* To start a new F# WASM Bolero application

```cs
dotnet new bolero-app -o HelloWorld
```

* To install the Nyancat tool:

```cs
dotnet tool install --global nyancat --version 1.4.0
```
