# Currency Exchange Service - Java Swing GUI

This is a simple currency exchange desktop application built using Java Swing. It allows users to input a passport number and an amount in US Dollars (USD), then converts the amount to a selected currency (British Pound or Canadian Dollar) and displays the result.

## Features

- **Passport Number Input**: Field for entering the user's passport number.
- **USD Amount Input**: Field to enter the amount in US Dollars to be exchanged.
- **Currency Selection**: Dropdown to select the target currency (British Pound or Canadian Dollar).
- **Exchange Button**: Calculates and displays the converted amount using fixed exchange rates:
  - 1 USD = 0.71 GBP
  - 1 USD = 1.35 CAD
- **Clear Button**: Resets all input fields.
- **Print Transaction Button**: (Currently not implemented with functionality).

## How to Run

1. Make sure you have Java installed (JDK 8 or higher).
2. Compile the file:

   ```bash
   javac CurrencyExchangeApp.java
