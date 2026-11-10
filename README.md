# SpaceX Falcon 9 & Falcon Heavy Launch Telemetry & Landing Analytics

[![Author](https://img.shields.io/badge/Author-M%20Akshay%20Sharma-indigo?style=for-the-badge&logo=github)](https://github.com/akshaysharma2005)
[![Category](https://img.shields.io/badge/Domain-Aerospace%20Analytics%20%26%20Machine%20Learning-blue?style=for-the-badge)](https://github.com/akshaysharma2005/spacex-falcon9-falcon-heavy-eda)
[![Repository](https://img.shields.io/badge/GitHub-spacex-falcon9-falcon-heavy-eda-emerald?style=for-the-badge&logo=github)](https://github.com/akshaysharma2005/spacex-falcon9-falcon-heavy-eda)

Exploratory telemetry of Falcon 9 and Falcon Heavy orbital launches, landing success rates, booster reusability economics, and orbital profiles.

---

## 🚀 Interactive Web Dashboard

This repository features an interactive web application with dynamic analytical calculators, live visual playgrounds, and interactive Chart.js visualizations.

- **Local Host Link**: [http://localhost:8080/EDA-SpaceX-Launches-Falcon9-and-Falcon-Heavy-with-Python/index.html](http://localhost:8080/EDA-SpaceX-Launches-Falcon9-and-Falcon-Heavy-with-Python/index.html)
- **Standalone Launch**: Open `index.html` in any modern web browser or serve via:
  ```bash
  python3 -m http.server 8080
  ```

---

## 📊 Key Metrics & Highlights

| Metric | Measured Value | Context |
| :--- | :--- | :--- |
| **Orbital Launches** | 168+ | Falcon 9 & Falcon Heavy |\n| **Landing Success Rate** | 92.4% | First-stage recovery |\n| **Turnaround Record** | 21 Days | Booster re-flight speed |\n| **Cost Reduction** | ~60% | Compared to expendable rockets |

---

## 🛠️ Tech Stack & Methodology

- **Domain**: Aerospace Analytics & Machine Learning
- **Tags & Frameworks**: `Python` `Pandas` `Folium` `Aerospace Data` `Logistic Regression`
- **Interactive UI**: HTML5, Tailwind CSS, Chart.js, FontAwesome

---

## 💡 Strategic Insights & Key Findings

- **Reusability Economics**: SpaceX lowered marginal launch cost from $62M to under $28M per mission through booster refurbishment.
- **ASDS vs RTLS**: Over 68% of recoveries require Autonomous Spaceport Drone Ships due to high-energy GTO downrange velocity.
- **Falcon Heavy Lift**: Falcon Heavy triples payload to LEO (63,800 kg) using 27 synchronized Merlin 1D engines.
- **Predictive Machine Learning**: Classification trees achieve 93.3% accuracy predicting landing success using payload mass, orbit, and launch site features.

---

## 💻 How to Run Locally

### 1. View the Web Dashboard
```bash
python3 -m http.server 8080
# Open http://localhost:8080/EDA-SpaceX-Launches-Falcon9-and-Falcon-Heavy-with-Python/index.html
```

### 2. Run the Analysis Notebook
```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn
jupyter notebook
```

---

## 👤 Author

**M Akshay Sharma**  
- **GitHub**: [@akshaysharma2005](https://github.com/akshaysharma2005)  
- **Email**: akshaysharma200508@gmail.com
