# Ninject.Extensions.Factory [![NuGet Version](http://img.shields.io/nuget/v/Ninject.Extensions.Factory.svg?style=flat)](https://www.nuget.org/packages/Ninject.Extensions.Factory/) [![NuGet Downloads](http://img.shields.io/nuget/dt/Ninject.Extensions.Factory.svg?style=flat)](https://www.nuget.org/packages/Ninject.Extensions.Factory/)

This Ninject extension allows to create factory implementations automatically.

This fork is paired with Ninject 3.2.3 and is intended for .Net Core 1. All unit tests are green except for two.
Castle interceptor IS NOT supported. Lazy<T> auto resolving IS NOT supported.
For additonal information please refer https://github.com/ninject/Ninject.Extensions.Factory/issues/35

Please note: I think it's risky to use it in a production environment.


To compile it in Visual Studio Code please
1) run VS Code
2) open folder Ninject.Extensions.Factory/src in windows explorer; use !create_link.cmd to create a symbolic link to Ninject root repository; modify it if you need.
3) open folder Ninject.Extensions.Factory/src in VS Code
4) press Ctrl+` to open terminal
5) execute

dotnet restore .\Ninject.Extensions.Factory\Ninject.Extensions.Factory.csproj

dotnet restore .\Ninject.Extensions.Factory.Test\Ninject.Extensions.Factory.Test.csproj

dotnet build .\Ninject.Extensions.Factory\Ninject.Extensions.Factory.csproj

dotnet build .\Ninject.Extensions.Factory.Test\Ninject.Extensions.Factory.Test.csproj

dotnet test .\Ninject.Extensions.Factory.Test\Ninject.Extensions.Factory.Test.csproj



(for Russians: console encoding can be changed by this command: [Console]::OutputEncoding = [System.Text.Encoding]::UTF8 )


## Documentation

https://github.com/ninject/Ninject.Extensions.Factory/wiki
