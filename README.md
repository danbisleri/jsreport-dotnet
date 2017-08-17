# jsreport sdk for .NET

**Pdf rendering, Excel rendering and other reporting features right in the .NET core using [jsreport](https://jsreport.net).**

jsreport sdk for .net includes c# based rest client to the  reporting server as well as assemblies running local jsreport right from the .NET project. Please find the guides, documentation and get started examples in **[jsreport sdk documentation](https://jsreport.net/learn/dotnet-v2)**.

## Examples

|   |   |   |
|---|---|---|
|[Console](https://github.com/jsreport/jsreport-dotnet-example-consoleapp) | Example of integrating local jsreport into .net core console application |
|[Web](https://github.com/jsreport/jsreport-dotnet-example-webapp) | Example of integrating local jsreport into asp.net core mvc appliation |


## Repositories
The jsreport sdk for .NET consists of several repositories and nuget packages were each has its specific location and purpose.

|   |   |   |  |
|---|---|---|--|
|[jsreport.Client](https://github.com/jsreport/jsreport-dotnet-client) | [![Build status](https://ci.appveyor.com/api/projects/status/81t7e9mcyvb1bfb5?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-client) | [![NuGet](https://img.shields.io/nuget/v/jsreport.Client.svg)](https://nuget.org/packages/jsreport.Client) |
|[jsreport.Local](https://github.com/jsreport/jsreport-dotnet-local) | [![Build status](https://ci.appveyor.com/api/projects/status/10hxkffrxlywr3k1?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-local) | [![NuGet](https://img.shields.io/nuget/v/jsreport.Local.svg)](https://nuget.org/packages/jsreport.Local) |
|[jsreport.AspNetCore](https://github.com/jsreport/jsreport-dotnet-aspnetcore) | [![Build status](https://ci.appveyor.com/api/projects/status/4vyvsocrvn3en7os?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-aspnetcore) | [![NuGet](https://img.shields.io/nuget/v/jsreport.AspNetCore.svg)](https://nuget.org/packages/jsreport.AspNetCore) |
|[jsreport.Types](https://github.com/jsreport/jsreport-dotnet-types) | [![Build status](https://ci.appveyor.com/api/projects/status/sx90dahobt3dhr2f?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-types) | [![NuGet](https://img.shields.io/nuget/v/jsreport.Types.svg)](https://nuget.org/packages/jsreport.Types) |
|[jsreport.Shared](https://github.com/jsreport/jsreport-dotnet-shared) | [![Build status](https://ci.appveyor.com/api/projects/status/nl2evif6uho2y7ha?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-shared) | [![NuGet](https://img.shields.io/nuget/v/jsreport.Shared.svg)](https://nuget.org/packages/jsreport.Shared) |
|[jsreport.Binary](https://github.com/jsreport/jsreport-dotnet-binary) | [![Build status](https://ci.appveyor.com/api/projects/status/o2xkoca4gtloxayx?svg=true)](https://ci.appveyor.com/project/pofider/jsreport-dotnet-binary) | [![NuGet](https://img.shields.io/nuget/v/jsreport.Binary.svg)](https://nuget.org/packages/jsreport.Binary) |

## Development and contributions

**We are looking forward every contribution!**  
You can follow these steps to startup your local environment:

1. install [VS 2017.3](https://www.visualstudio.com/) 
2. clone this repository
3. run `clone-all.bat`
4. open `jsreport.development.sln`

You can of course also open each individual repository separately, but this approach is probably the most convenient.

## Roadmap

1. Create demo screen cast
2. Release linux and osx binary package

## License
MIT