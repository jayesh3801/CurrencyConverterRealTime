# Currency Converter Application

This application allows you to convert currency based on the latest exchange rates. It utilizes the Open Exchange Rates API to fetch the latest rates.

## Features

- Convert currency from one type to another.
- Supports various currencies including INR, JPY, USD, NZD, EUR, CAD, ISK, PHP, DKK, CZK.

## How to Use

1. Enter the amount you want to convert in the "Enter Amount" field.
2. Select the currency you are converting from in the "From" dropdown menu.
3. Select the currency you want to convert to in the "To" dropdown menu.
4. Click the "Convert" button to see the converted value.

## Dependencies

- Json.NET - A popular high-performance JSON framework for .NET.

## Usage

To use this application, simply download or clone the repository and open the project in Visual Studio. Make sure to install the Newtonsoft.Json package via NuGet to resolve the dependencies.

### Code Overview

**MainWindow.xaml.cs**: This file contains the code-behind for the main window of the application. It handles the logic for fetching exchange rates, performing conversions, and updating the UI.

**MainWindow.xaml**: This XAML file defines the layout and design of the application's main window. It includes various UI elements like labels, textboxes, buttons, and dropdown menus.

### Getting Started

1. Clone the repository
2. Open the solution in Visual Studio and build the project.
3. Install the Newtonsoft.Json package via NuGet if not already installed.
4. Run the application.

*Note*: This application requires an internet connection to fetch the latest exchange rates from the Open Exchange Rates API.

## License

This project is licensed under the MIT License.
