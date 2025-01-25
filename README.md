# Currency-Exchange-Application(React.js)
This React-based Currency Exchange Application allows users to convert currency values in real-time using the FreeCurrencyAPI.
Features:
Enter an amount and select currencies for conversion.
Real-time exchange rate retrieval via API.
Conversion results displayed with three decimal precision.
Simple and responsive UI with an exchange button.

How It Works:
State Management:amount, fromCurrency, toCurrency, and result are managed using useState.

API Call:The exchange function fetches exchange rates from the API and calculates the result:
(response.data.data[toCurrency] * amount).toFixed(3);

UI Components:Input for amount, dropdowns for currency selection, and an exchange button.

Usage Instructions:
Install dependencies: npm install
Run the app: npm start 
Enter values and click "Çevir" to get the result.
