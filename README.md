# Crypto Marketplace

Crypto Marketplace is a responsive web application built with React and Vite that allows users to view real-time cryptocurrency market data, search for specific coins, and view detailed information and historical price charts.

## Features

- Display a list of the top cryptocurrencies by market cap with live price, 24h change, and market cap  
- Search functionality to filter coins by name  
- Currency selection (USD, EUR, GBP) with corresponding symbols  
- Detailed coin page with current price stats and a 10-day price history chart  
- Responsive design with mobile-friendly layouts  

## Technologies

- React 19  
- Vite for development and build tooling  
- React Router DOM for routing  
- React Google Charts for data visualization  
- CoinGecko API for market data  

## Project Structure

```
crypto-marketplace/
├── public/
│   └── index.html
├── src/
│   ├── assets/
│   │   ├── logo.png
│   │   └── arrow_icon.png
│   ├── components/
│   │   ├── Navbar/
│   │   │   ├── Navbar.jsx
│   │   │   └── Navbar.css
│   │   ├── Footer/
│   │   │   ├── Footer.jsx
│   │   │   └── Footer.css
│   │   └── LineChart/
│   │       ├── LineChart.jsx
│   │       └── LineChart.css
│   ├── context/
│   │   └── CoinContext.jsx
│   ├── pages/
│   │   ├── Home/
│   │   │   ├── Home.jsx
│   │   │   └── Home.css
│   │   └── Coin/
│   │       ├── Coin.jsx
│   │       └── Coin.css
│   ├── index.css
│   ├── main.jsx
│   └── App.jsx
├── .gitignore
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (>=14.x) and npm

### Installation

```bash
git clone https://github.com/Jose-Pimenta/crypto-marketplace.git
cd crypto-marketplace
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

Open your browser at `http://localhost:5173`.

### Build

To build the production bundle:

```bash
npm run build
npm run preview
```

## API

All market data is fetched from the [CoinGecko API](https://www.coingecko.com/en/api) using a demo API key. For production, you should replace the demo key with your own.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Jose Pimenta
