# Crypto Dashboard

The **Crypto Dashboard** is a sleek and responsive React-based application designed for crypto enthusiasts and ICO projects. This lightweight frontend displays real-time cryptocurrency data and an ICO countdown timer, making it perfect for quick deployments and engaging presentations.

---

## Features

### 1. **Live Crypto Data**
- Fetches real-time cryptocurrency information (price, market cap, 24h price change) using the CoinGecko API.
- Displays the top cryptocurrencies in an easy-to-read card format.

### 2. **Dynamic ICO Countdown Timer**
- Includes a live countdown timer to track the time remaining until the end of an ICO.
- Updates in real time to maintain accuracy.

### 3. **Responsive Design**
- Fully responsive layout that adapts seamlessly to any screen size.
- Clean and modern UI for an excellent user experience.

### 4. **Quick Setup and Lightweight**
- Minimal dependencies for easy setup.
- Designed for fast implementation and deployment.

---

## Installation and Setup

Follow these steps to run the Crypto Dashboard on your local machine:

### 1. Clone the Repository
```bash
git clone <your-repo-link>
cd crypto-dashboard
```

### 2. Install Dependencies
Make sure you have [Node.js](https://nodejs.org/) installed, then run:
```bash
npm install
```

### 3. Run the Application
```bash
npm start
```
The app will be available at `http://localhost:3000`.

---

## Customization

### 1. **ICO End Time**
Update the `ICO_END_TIME` variable in the `App.js` file to set your desired ICO countdown date:
```javascript
const ICO_END_TIME = new Date("2024-12-31T23:59:59Z").getTime();
```

### 2. **Styling**
Customize the styles in `App.css` to match your branding and design preferences.

### 3. **API Configuration**
If needed, adjust the API parameters in the `fetchCryptoData` function in `App.js` to fetch different data or modify the number of cryptocurrencies displayed.

---

## Deployment

### 1. Deploy on GitHub Pages
- Build the app:
```bash
npm run build
```
- Deploy using a tool like [gh-pages](https://github.com/tschaub/gh-pages) or manually upload the `build` folder to your GitHub Pages repository.

### 2. Deploy on Vercel
- Install the Vercel CLI:
```bash
npm install -g vercel
```
- Run:
```bash
vercel
```

---

## Contributing
Feel free to fork this repository and submit pull requests. Contributions are welcome to improve functionality, add features, or enhance design.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

## Acknowledgments
- **CoinGecko API** for providing real-time cryptocurrency data.
- The **Legion.cc Community** for inspiration and collaboration.

---

🚀 Start building and showcasing your crypto projects today with the Crypto Dashboard!
