# Cryptocurrency Tracker

A modern web application built with React that allows users to track cryptocurrency prices, market data, and detailed information about various cryptocurrencies using the CoinGecko API.

## Features

- Real-time cryptocurrency price tracking
- Detailed coin information including:
  - Current price
  - 24-hour price changes
  - Market cap
  - Circulating supply
  - Price history (1h, 24h, 7d, 14d, 30d, 1yr)
  - Coin descriptions
- Responsive design for mobile and desktop
- Interactive UI with hover effects
- Clean and modern user interface

## Technologies Used

- React.js
- Axios for API calls
- React Router for navigation
- DOMPurify for sanitizing HTML content
- CSS for styling
- CoinGecko API for cryptocurrency data

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cryptocurrency-tracker.git
```

2. Navigate to the project directory:
```bash
cd cryptocurrency-tracker
```

3. Install dependencies:
```bash
npm install
# or
yarn install
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open your browser and visit `http://localhost:5173`

## API Usage

This project uses the CoinGecko API. Please note that the free tier has rate limits:
- 10-50 calls per minute
- No API key required for basic endpoints

For production use, consider:
- Implementing request caching
- Using the CoinGecko Pro API
- Setting up a backend proxy server

## Project Structure

```
src/
├── components/
│   ├── Coins.jsx        # Main coins list component
│   ├── CoinItem.jsx     # Individual coin item component
│   └── Coins.css        # Styling for coins components
├── routes/
│   ├── Coin.jsx         # Detailed coin view component
│   └── Coin.css         # Styling for coin details
└── App.jsx              # Main application component
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [CoinGecko API](https://www.coingecko.com/en/api) for providing cryptocurrency data
- [React](https://reactjs.org/) for the frontend framework
- [React Router](https://reactrouter.com/) for routing
- [DOMPurify](https://github.com/cure53/DOMPurify) for HTML sanitization 