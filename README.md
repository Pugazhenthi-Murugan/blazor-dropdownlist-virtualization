# Blazor Dropdownlist Virtualization Sample

A compact sample demonstrating how to enable virtualization in the [Blazor DropDownList](https://www.syncfusion.com/blazor-components/blazor-dropdown-list) component. This project shows a performant dropdown bound to a large data set using UI virtualization.

## Overview

This sample illustrates how to configure and use virtualization with the Blazor DropDownList component to efficiently render and interact with very large lists. Virtualization reduces memory and rendering work by creating DOM elements only for visible items.

## Features

- High-performance rendering optimized for large datasets
- Efficient memory usage through UI virtualization techniques
- Full keyboard navigation support for accessibility
- Complete project structure supporting multiple deployment scenarios
- Clean, straightforward implementation ready for real-world applications

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-dropdownlist-virtualization.git
cd blazor-hybrid-app-custom-form-validation
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

- Demo: https://blazor.syncfusion.com/demos/dropdown-list/virtualization?theme=fluent
- Documentation: https://blazor.syncfusion.com/documentation/dropdown-list/virtualization#keyboard-interaction