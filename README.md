# Real-Time Weather Data Dashboard

A simple Python project that fetches **real-time weather data** from the [OpenWeatherMap API](https://openweathermap.org/api) and displays results in a continuously updating table inside **Jupyter Notebook**.

---

## 📌 Features
- Fetches live weather data for multiple cities.
- Updates results **every second** automatically.
- Displays data in a clean **pandas DataFrame**.
- Keeps your API key **secure in a `config.py` file**.
- Ready to run on **Jupyter Notebook**.

---

## 🛠 Requirements
- Python 3.8+
- Jupyter Notebook
- Dependencies: `requests`, `pandas`

---

## ⚙️ Installation

1. Clone this repository or download the project files.
   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
   cd weather-dashboard
   ```

2. Create and activate a virtual environment (optional but recommended).
   ```bash
   python -m venv venv
   source venv/bin/activate   # Mac/Linux
   venv\Scripts\activate      # Windows
   ```

3. Install dependencies.
   ```bash
   pip install -r requirements.txt
   ```

4. Create a `config.py` file in the project root:
   ```python
   API_KEY = "your_real_api_key_here"
   ```

---

## ▶️ Usage

1. Launch Jupyter Notebook:
   ```bash
   python3 -m notebook
   ```

2. Open **`Weather_Dashboard.ipynb`**.

3. Run all cells.  
   - The table will refresh **every second** with updated weather info.
   - Stop the loop anytime using the Jupyter **Stop (■)** button.

---

## 📊 Example Output
| City      | Temperature (°C) | Humidity (%) | Description |
|-----------|------------------|--------------|-------------|
| London    | 15.42            | 82           | Light Rain  |
| Tokyo     | 28.15            | 70           | Clear Sky   |
| New York  | 22.87            | 65           | Cloudy      |

---

## 🔒 Security Note
⚠️ Never commit your **API key** to GitHub or share it publicly. Always keep it in `config.py` (ignored in `.gitignore` if using Git).

---

## 📜 License
This project is open-source and available under the [Apache License](LICENSE).
