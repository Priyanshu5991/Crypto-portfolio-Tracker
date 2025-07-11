Crypto Portfolio Tracker
A real-time cryptocurrency portfolio tracker built using Python and Flask, allowing users to track their crypto assets, view real-time prices, and visualize portfolio performance.

Features
- 🔄 Real-time cryptocurrency prices
- 📊 Dynamic portfolio performance tracking
- 📈 Chart visualization (e.g., pie chart for holdings)
- 💰 Profit/loss calculation
- 🧩 API integration with CoinGecko
- 📁 Organized code structure with templates and static assets

Tech Stack
- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript (with Chart.js)
- **APIs:** CoinGecko API for real-time price data

Getting Started
1. Clone the Repository

```bash
git clone https://github.com/priyanshu5991/CryptoPortfolioTracker.git
cd CryptoPortfolioTracker
````

2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
* On Windows:
```bash
venv\Scripts\activate
```

* On macOS/Linux:
```bash
source venv/bin/activate
```

4. Install Dependencies
```bash
pip install -r requirements.txt
```

5. Run the Application
```bash
python app.py
```

Then open your browser and navigate to `http://127.0.0.1:5000/`.

---

 Project Structure
```bash
CryptoPortfolioTracker/
│
├── static/
│   ├── css/
│   ├── js/
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
└── README.md
```

 Future Improvements
* User login and registration
* Wallet import via address
* Email alerts for price changes
* Export reports to CSV/PDF

License
This project is licensed under the MIT License.

Author
**Priyanshu Tonk**
[GitHub](https://github.com/priyanshu5991)
