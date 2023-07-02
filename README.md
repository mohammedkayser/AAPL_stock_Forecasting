# Shiny App for Time Series Forecasting of AAPL Stock Prices

This is a Shiny app that provides a graphical interface for visualizing and forecasting AAPL stock prices using time series analysis. 

The app utilizes the Prophet package in R for forecasting and dygraphs for interactive visualization.

## Project Structure

The project directory contains the following files:

- `app.R`: This file contains the code for the Shiny app, including the user interface (UI) and server logic.
- `README.md`: This file provides an overview and instructions for the project.
- Other necessary R libraries are listed in the code and should be installed prior to running the app.

## Usage

1. Clone or download this repository to your local machine.
2. Open the R project file `Forecasting_Stock_Prices_AAPL.Rproj` in RStudio.
3. Open the `app.R` file in RStudio.
4. Run the `app.R` script to launch the Shiny app.
5. The app will display a dygraphs plot showing the historical stock prices of AAPL.
6. Adjust the time period using the slider input to view specific ranges of stock prices.
7. The app also includes a forecasted line (in red) representing the predicted stock prices for the future period.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## Installation

To run the Shiny app, please ensure that you have the required R packages installed. You can install them using the following commands:

```R
# Install required packages
install.packages(c("quantmod", "shiny", "prophet", "tidyverse", "dygraphs", "xts", "lubridate"))
