# Currency Converter App

This Currency Converter App allows users to convert an amount from one currency to another, with real-time conversion rates fetched using a custom `useCurrencyInfo` hook. The app features input fields to specify the amount, the original currency, and the target currency, along with a "swap" function to switch the selected currencies. 

## Features

- Currency conversion between various currencies.
- Swap functionality to easily switch between "From" and "To" currencies.
- Beautiful UI with a custom background and responsive design using Tailwind CSS.

## Technologies Used

- **React**: Component-based architecture for building the UI.
- **Custom Hook**: `useCurrencyInfo` to fetch and manage currency data.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **JavaScript**: Logic and interactivity for the app.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/bansal9855/Currency-Converter.git
    cd 06currencyconverter
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Run the app**:
    ```bash
    npm run dev
    ```

## Sample Input and Output

### Example 1
- **Input**:
  - Amount: `100`
  - From Currency: `USD`
  - To Currency: `INR`
- **Action**: Press the "Convert" button.
- **Output**: `100 USD` converted to `INR` displays approximately `8410 INR` (assuming a conversion rate of 1 USD = 84.09 INR).

### Example 2 (Swap Function)
- **Input**: 
  - From Currency: `USD`
  - To Currency: `INR`
  - Initial Amount: `50` (in USD)
- **Action**: Click the "Swap" button.
- **Output**:
  - From Currency changes to `INR`, and To Currency changes to `USD`.
  - `Converted Amount` updates to approximately `0.6 USD` (assuming a conversion rate of 1 INR = 0.012 USD).

## License

This project is licensed under the MIT License.

