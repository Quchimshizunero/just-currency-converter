# JustCurrencyConverter

JustCurrencyConverter is a simple JavaScript library for converting currencies using a currency conversion API.

## Installation

To install JustCurrencyConverter, you can use npm:

```bash
npm install just-currency-converter
```

## Usage

```javascript
const JustCurrencyConverter = require('just-currency-converter');

// Initialize the converter with your API key
const converter = new JustCurrencyConverter('YOUR_API_KEY');

// Convert currency
converter.convert(100, 'USD', 'EUR')
  .then(result => {
    console.log(`Converted amount: ${result}`);
  })
  .catch(error => {
    console.error(`Conversion failed: ${error.message}`);
  });
```

Replace `'YOUR_API_KEY'` with your actual API key for the currency conversion service you're using.

## API Key

You can obtain an API key from the currency conversion service provider. Make sure to keep your API key secure and do not expose it publicly.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
