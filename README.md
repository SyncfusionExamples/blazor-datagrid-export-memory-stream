# Blazor DataGrid Export Memory Stream

A production-ready sample demonstrating how to export  [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) data as memory streams for PDF generation and advanced data handling. This project showcases both basic memory stream export and advanced scenarios like merging multiple PDFs.

## Overview

This repository contains a complete Blazor application that demonstrates efficient data export patterns using the  DataGrid component. Instead of writing directly to disk, the application exports grid data to in-memory streams, enabling flexible post-processing, dynamic content generation, and optimized performance for web-based scenarios.

## Features

- **Basic PDF Export**: Export grid data directly as a PDF memory stream
- **Advanced PDF Merging**: Combine multiple grid exports with custom styling into a single PDF
- **Custom Theme Support**: Apply custom colors, fonts, and borders to exported PDFs
- **Server-Side & Client-Side Rendering**: Leverages Blazor's interactive capabilities
- **Toolbar Integration**: Export functionality integrated into the DataGrid toolbar
- **Client-Side File Download**: Seamless download experience using JavaScript interop

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-export-memory-stream.git
cd blazor-datagrid-export-memory-stream/GridPDFStream
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- Export Documentation: https://blazor.syncfusion.com/documentation/datagrid/pdf-export#exporting-grid-data-as-stream
- Export Feature Demo: https://blazor.syncfusion.com/demos/datagrid/exporting?theme=fluent2

