# Crypto Price Tracker

A Next.js application that displays live cryptocurrency price data using the CoinGecko API.

## Overview

This application tracks prices for popular cryptocurrencies and displays their current price, symbol, and 24-hour price change percentage. The data is automatically refreshed every 30 seconds to provide up-to-date information.

## Features

- Live tracking of cryptocurrency prices (Bitcoin, Ethereum, Solana, Polygon, Dogecoin)
- 24-hour price change percentage with visual indicators (green for positive, red for negative)
- Auto-refresh data every 30 seconds
- Search and add additional cryptocurrencies
- Sort cryptocurrencies by price change (ascending/descending)
- Responsive design

## Technologies Used

- **Framework**: Next.js
- **Data Fetching**: React Query (@tanstack/react-query)
- **API**: CoinGecko API
- **Styling**: Tailwind CSS

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crypto-tracker.git
   cd crypto-tracker
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

4. Build for production:
   ```bash
   npm run build
   ```

5. Start the production server:
   ```bash
   npm start
   ```

## Usage

- The main page displays a list of cryptocurrencies with their current price and 24-hour change
- Click the sort button to toggle between ascending and descending order based on 24-hour price change

## API Reference

This project uses the CoinGecko API to fetch cryptocurrency price data:
- Endpoint: `https://api.coingecko.com/api/v3/coins/markets`
- Parameters:
  - `vs_currency=usd` - Convert prices to USD
  - `ids=bitcoin,ethereum,etc` - Specify which cryptocurrencies to fetch
  - `price_change_percentage=24h` - Include 24-hour price change data


## License

[MIT](LICENSE)
