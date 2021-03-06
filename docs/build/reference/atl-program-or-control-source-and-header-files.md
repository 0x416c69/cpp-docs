---
title: "ATL Program or Control Source and Header Files"
ms.date: "11/04/2016"
helpviewer_keywords: ["file types [C++], ATL source and headers"]
ms.assetid: cb65372f-4880-4007-b582-a52eaa568fd1
---
# ATL Program or Control Source and Header Files

The following files are created when you create an ATL project in Visual Studio, depending on the options you select for the project you create.

All of these files are located in the *Projname* directory, and in either the Header Files (.h files) folder or Source Files (.cpp files) folder in Solution Explorer.

|File name|Description|
|---------------|-----------------|
|*Projname*.h|The main include file containing the C++ interface definitions and GUID declarations of the items defined in ATLSample.idl. It is regenerated by MIDL during compilation.|
|*Projname*.cpp|The main program source file. It contains the implementation of your DLL's exports for an in-process server and the implementation of `WinMain` for a local server. For a service, this additionally implements all the service management functions.|
|Resource.h|The header file for the resource file.|
|StdAfx.cpp|Includes the files StdAfx.h and Atlimpl.cpp.|
|StdAfx.h|Includes the ATL header files.|

## See also

[File Types Created for Visual Studio C++ projects](file-types-created-for-visual-cpp-projects.md)<br>
[MFC Program or Control Source and Header Files](mfc-program-or-control-source-and-header-files.md)<br>
[CLR Projects](files-created-for-clr-projects.md)
