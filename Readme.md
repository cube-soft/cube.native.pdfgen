Cube.Native.Nuspec
====

[![NuGet](https://img.shields.io/nuget/v/Cube.Native.Ghostscript.svg?label=ghostscript)](https://www.nuget.org/packages/Cube.Native.Ghostscript)
[![NuGet](https://img.shields.io/nuget/v/Cube.Native.Pdfium.svg?label=pdfium)](https://www.nuget.org/packages/Cube.Native.Pdfium)
[![NuGet](https://img.shields.io/nuget/v/Cube.Native.Pdfium.Lite.svg?label=pdfium.lite)](https://www.nuget.org/packages/Cube.Native.Pdfium.Lite)

Cube.Native.Nuspec is a repository to pack third-party unmanaged libraries or their customized version as a NuGet manner. These packages are used in Cube.* projects.

## Ghostscript

[Cube.Native.Ghostcript](https://www.nuget.org/packages/Cube.Native.Ghostscript) is an unofficial NuGet package for gsdll32.dll and related resources, which are part of the [Ghostscript](https://www.ghostscript.com/). Note that the package renames gsdll64.dll (for x64 library) to gsdll32.dll. The package is used in the [Cube.Pdf](https://github.com/cube-soft/Cube.Pdf) project.

## PDFium

[Cube.Native.Pdfium](https://www.nuget.org/packages/Cube.Native.Pdfium) and [Cube.Native.Pdfium.Lite](https://www.nuget.org/packages/Cube.Native.Pdfium.Lite) are unofficial NuGet packages for the [PDFium](https://pdfium.googlesource.com/pdfium/). Note that the Cube.Native.Pdfium.Lite package removes V8 and XFA options from the Cube.Native.Pdfium package. These packages are used in the [Cube.Pdf](https://github.com/cube-soft/Cube.Pdf) project.