---
title: '.Net Core Class Libraries - Build, Target, Use them'
tags:
  - .Net Core
url: 492.html
id: 492
categories:
  - ASP.NET Core 1.0
---

.NET [Core class libraries](http://dotnet.readthedocs.io/en/latest/concepts/class-libraries.html) combines the concept of platform*specific and portable library concept into a single model that provides the best of both.

Why .NET Core class libraries are special?
------------------------------------------

*   Write C# code in such a way you can target them for Full .NET framework or .NET Core
*   Simplified way for maintaining code for different frameworks.
*   Can leverage PCL (Portable Class Libraries) also.
*   Better than using PCL for they support more APIs than PCL
*   Most importantly, .NET Core class libraries can be cross platform esp for ASP.NET Core apps.

What we will learn?

1.  Build .NET Core class libraries using Visual Studio 2015.
2.  Target them to use full .NET frameworks like .NET 4, .NET 5, .NET 6 and .NET Core apps like ASP.NET Core apps.
3.  Use these class libraries in simple ASP.NET Core apps, WPF, Console Apps.

> We need Visual Studio 2015 and .NET Core SDK installed with ASP.NET Core web tools

Open Visual Studio 2015, Create New