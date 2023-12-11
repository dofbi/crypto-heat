# Crypto Heat

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://semver.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Welcome to Crypto Heat! 🚀 A simple tool to track cryptocurrency price change on 24 hour rolling window

---

## Features

📈 Displays top cryptocurrencies in gain or loss.
🔍 Option to limit the number of displayed results.
🌐 Supports English and French languages.

---

## Usage

To use Crypto Heatmap, follow these simple steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/dofbi/crypto-heat.git
   cd crypto-heat

2. Set the BINANCE_API environment variable:

   ```shell
   export BINANCE_API="https://www.binance.com/fapi/v1/ticker/24hr"
   chmod +x ./bin/cryptoheat

3. Run the script specifying options as needed:

   ```shell
   ./bin/cryptoheat -n 20 -u


## Data Source

The data displayed is retrieved from the [Binance API](https://binance-docs.github.io/apidocs/futures/en/#24hr-ticker-price-change-statistics).

## Contributions

We welcome contributions! 🙌 Feel free to improve the script, fix bugs, or add features. Check the [CONTRIBUTING](CONTRIBUTING) file for how to contribute.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
