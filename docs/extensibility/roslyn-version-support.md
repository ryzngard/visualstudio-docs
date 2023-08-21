---
title: Supported Roslyn package version mappings
description: This article shows which .NET compiler platform (Roslyn) package versions are supported for different versions of Visual Studio.
ms.date: 04/29/2019
ms.topic: reference
helpviewer_keywords:
- roslyn package versions
author: maiak
ms.author: maiak
manager: jmartens
ms.technology: vs-ide-sdk
ms.workload:
- vssdk
---
# .NET compiler platform package version reference

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]

The following table shows which [.NET compiler platform (Roslyn) package](https://www.nuget.org/packages/Microsoft.Net.Compilers/) versions are supported for different versions of Visual Studio.

As an example, to ensure that your custom analyzer works on all versions of Visual Studio 2017, it should target version 2.0 of Microsoft.Net.Compilers.

| Roslyn package version | Minimum supported Visual Studio version |
| - | - |
| 4.8.0 | Visual Studio 2022 Version 17.8 (Preview) |
| 4.7.0 | Visual Studio 2022 Version 17.7 |
| 4.6.0 | Visual Studio 2022 version 17.6 |
| 4.5.0 | Visual Studio 2022 version 17.5 |
| 4.4.0 | Visual Studio 2022 version 17.4 |
| 4.3.1 | Visual Studio 2022 version 17.3 |
| 4.2.0 | Visual Studio 2022 version 17.2 |
| 4.1.0 | Visual Studio 2022 version 17.1 |
| 4.0.1 | Visual Studio 2022 RTM |
| 3.11.0 | Visual Studio 2019 version 16.11 |
| 3.10.0 | Visual Studio 2019 version 16.10 |
| 3.9.0 | Visual Studio 2019 version 16.9 |
| 3.8.0 | Visual Studio 2019 version 16.8 |
| 3.7.0 | Visual Studio 2019 version 16.7 |
| 3.6.0 | Visual Studio 2019 version 16.6 |
| 3.5.0 | Visual Studio 2019 version 16.5 |
| 3.4.0 | Visual Studio 2019 version 16.4 |
| 3.3.1 | Visual Studio 2019 version 16.3 |
| 3.2.1 | Visual Studio 2019 version 16.2 |
| 3.1.0 | Visual Studio 2019 version 16.1 |
| 3.0.0 | Visual Studio 2019 RTM |
| 2.10.0 | Visual Studio 2017 version 15.9 |
| 2.9.0 | Visual Studio 2017 version 15.8 |
| 2.8.2 | Visual Studio 2017 version 15.7 |
| 2.7.0 | Visual Studio 2017 version 15.6 |
| 2.6.1 | Visual Studio 2017 version 15.5 |
| 2.4.0 | Visual Studio 2017 version 15.4 |
| 2.3.2 | Visual Studio 2017 version 15.3 |
| 2.2.0 | Visual Studio 2017 version 15.2 |
| 2.1.0 | Visual Studio 2017 version 15.1 |
| 2.0.0 | Visual Studio 2017 RTM |
| 1.3.2 | Visual Studio 2015 update 3 |
| 1.2.2 | Visual Studio 2015 update 2 |
| 1.1.1 | Visual Studio 2015 update 1 |
| 1.0.1 | Visual Studio 2015 RTM |

> [!TIP]
> For Roslyn packages where the minimum supported Visual Studio version is a Visual Studio 2017 version, all versions of Visual Studio 2019 are also supported because they came later.

## See also

- [.NET Compiler Platform SDK](/dotnet/csharp/roslyn-sdk/)
- [Get started with Roslyn analyzers](getting-started-with-roslyn-analyzers.md)
