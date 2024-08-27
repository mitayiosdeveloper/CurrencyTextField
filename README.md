This file handles the visibility of currency formatting, specifically for displaying European currency types.

Usage Example:

CurrencyTextField(placeholder: "Placeholder Text", value: $viewModel.Amount, currencyCode: "EUR", hideCurrencyCode: true)
    .keyboardType(.numberPad)

From ViewModel:

@Published var contractAmount: Double?

Placeholder Text: You can customize this as needed.
viewModel.Amount: This represents the amount value that updates based on user input.
currencyCode: Set this to the desired currency (e.g., "EUR" for Euros).
