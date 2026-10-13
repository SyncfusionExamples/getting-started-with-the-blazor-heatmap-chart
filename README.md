# Getting Started with the Syncfusion Blazor HeatMap Chart

## Overview

This sample demonstrates how to create and configure a Syncfusion [Blazor HeatMap Chart](https://www.syncfusion.com/blazor-components/blazor-heatmap-chart). The HeatMap visualizes sales revenue data for employees across multiple days using a two-dimensional data matrix. The implementation showcases category-based axes, fixed color palettes, bubble-size cell rendering, nullable data handling, and custom value formatting. It serves as a practical reference for developers who want to build interactive data visualization experiences using the Syncfusion Blazor HeatMap component.

## Key Features

- Uses the `SfHeatMap` component to render HeatMap visualizations.
- Binds HeatMap data through the `DataSource` property using a two-dimensional nullable integer array (`int?[,]`).
- Configures the HeatMap title using `HeatMapTitleSettings`.
- Uses `HeatMapPaletteSettings` with `PaletteType.Fixed` to define a fixed color range.
- Configures custom palette colors through multiple `HeatMapPalette` entries.
- Customizes cell rendering using `HeatMapCellSettings`.
- Uses `CellType.Rect` for rectangular HeatMap cells.
- Uses `BubbleType.Size` to represent values through bubble sizing.
- Formats displayed values with `Format="${value}"`.
- Initializes the data source during component startup using the `OnInitialized()` lifecycle method.

## Prerequisites

* Visual Studio 2022

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore NuGet packages.
4. Build the solution.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the startup project directory for the hosted application.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Solution file for the sample application.

- `Client/Pages/Index.razor` — Main HeatMap sample page containing the `SfHeatMap` implementation, data source initialization, axis definitions, palette configuration, and cell settings.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://help.syncfusion.com/chart-sdk/blazor/heatmap-chart/getting-started-with-web-app).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.