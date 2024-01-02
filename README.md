# Crypto Converter

Crypto Converter is a web application that allows users to convert amounts between different cryptocurrencies and traditional currencies. The application involves calling a public currency conversion API, performing calculations on the server, and displaying the results on the client-side.

## Technical Stack

### Backend (Node.js & Express.js):

- Set up an API endpoint to fetch the top 100 cryptocurrencies and supported currencies (USD, EUR, etc).
- Set up an API endpoint that takes a source cryptocurrency, amount, and target currency (EUR, USD, etc) as parameters.
- Use the CoinMarketCap API to get real-time exchange rates of cryptocurrencies and top 100 cryptocurrencies.
- Perform the currency conversion between crypto and the selected currency (USD, EUR, etc) on the server and return the result.

### Frontend (React):

- Design a simple form where users can select a source cryptocurrency (fetched from API), input the amount, and select the target currency (USD, EUR, etc).
- Display the converted amount to the user.
- Ensure basic error handling and validation of user inputs.
- Impress users with a creative UI.


