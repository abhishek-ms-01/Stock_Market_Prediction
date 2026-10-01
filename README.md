<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=AlphaTrade&fontSize=90&fontColor=ffffff&fontAlignY=38&desc=Event-Driven%20Stock%20Market%20Prediction%20with%20RAG-LSTM&descAlignY=60&descSize=20&animation=fadeIn"/>

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=10B981&center=true&vCenter=true&width=850&lines=📈+Predict+Short-Horizon+Market+Direction;🧠+Combine+LSTM+Forecasting+with+RAG;📰+Connect+News+Sentiment+with+Price+Action;🛡️+Understand+Risk+Before+Making+Decisions" alt="Typing SVG" />

<br/>

<p>
  <img src="https://img.shields.io/badge/Status-Research%20Prototype-10B981?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-RAG%20%2B%20LSTM-4285F4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack-Next.js%20%7C%20FastAPI-111827?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Data-Market%20%2B%20News-0f766e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Research-f59e0b?style=for-the-badge" />
</p>

<p>
  <a href="https://www.stockmarketpredictionsystem.site/">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-Open_AlphaTrade-16a34a?style=for-the-badge" />
  </a>
  &nbsp;
  <a href="https://github.com/abhishek-ms-01/Stock_Market_Prediction/stargazers">
    <img src="https://img.shields.io/badge/⭐_Star_this_Repo-Show_Support-f59e0b?style=for-the-badge" />
  </a>
  &nbsp;
  <a href="https://github.com/abhishek-ms-01/Stock_Market_Prediction/issues">
    <img src="https://img.shields.io/badge/🐛_Report_Bug-Open_Issue-dc2626?style=for-the-badge" />
  </a>
</p>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>

<br/>

> ### _Market intelligence that combines numbers, news, and context._

<br/>

</div>

---

## 📈 What is AlphaTrade?

**AlphaTrade** is a full-stack stock market intelligence and prediction platform. It combines quantitative market features, technical indicators, financial-news retrieval, sentiment signals, risk analysis, and an LSTM forecasting model inside one investor-focused dashboard.

The platform is designed for research and decision support. It helps users explore market movement with:

- 📊 live and historical stock data
- 📐 RSI, MACD, SMA, returns, volatility, and volume features
- 📰 time-aware financial-news retrieval and sentiment analysis
- 🧠 LSTM-based short-horizon directional forecasting
- 🤖 RAG-powered conversational market analysis
- 🛡️ risk scoring, market-regime detection, and portfolio guidance

```text
📊 Market data + 📰 financial news  →  🧠 feature fusion  →  📈 forecast + 🛡️ risk context
```

> This project is an analytical research tool, not financial advice or an automated trading system.

---

## 📸 Platform Screenshots

<div align="center">

<table>
  <tr>
    <td align="center" width="50%">
      <img src="Screenshot 2026-10-01 101301.png" width="100%" alt="AlphaTrade Landing Page"/>
      <br/><br/><b>🏠 Landing Page — AlphaTrade Terminal</b>
    </td>
    <td align="center" width="50%">
      <img src="./screenshots/dashboard.png" width="100%" alt="Market Dashboard"/>
      <br/><br/><b>📊 Dashboard — Market Overview</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./screenshots/forecast.png" width="100%" alt="Forecast Page"/>
      <br/><br/><b>🧠 Forecast — Directional Prediction</b>
    </td>
    <td align="center" width="50%">
      <img src="./screenshots/indicators.png" width="100%" alt="Technical Indicators"/>
      <br/><br/><b>📈 Indicators — Technical and Sentiment Signals</b>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="./screenshots/ai-chat.png" width="100%" alt="AI Market Chat"/>
      <br/><br/><b>🤖 AI Chat — RAG Market Assistant</b>
    </td>
    <td align="center" width="50%">
      <img src="./screenshots/live-pipeline.png" width="100%" alt="Live Pipeline"/>
      <br/><br/><b>⚡ Live Pipeline — Backend Telemetry and Execution Flow</b>
    </td>
  </tr>
</table>

</div>

---

## ✨ Core Features

<div align="center">

| Module | Capability | Powered By |
| :---: | --- | :---: |
| 📈 **Forecast Engine** | Predict short-horizon market direction from engineered sequences | LSTM + Keras |
| 📰 **News Intelligence** | Retrieve relevant financial news and connect events to price movement | RAG + vector search |
| 📐 **Technical Analysis** | RSI, MACD, moving averages, returns, volatility, and volume signals | Pandas + NumPy |
| 🤖 **AI Market Chat** | Explain market context and answer questions using retrieved knowledge | RAG assistant |
| 🛡️ **Risk Analysis** | Analyze volatility, market regime, exposure, and portfolio signals | Risk engine |
| ⚡ **Live Pipeline** | Bring market and news data together for dashboard analysis | FastAPI + fetchers |

</div>

### 📈 LSTM Forecasting

> Turn engineered market history into an interpretable directional outlook.

- Builds sequences from technical and market features
- Uses an LSTM model stored at `backend/models/lstm_model.h5`
- Produces forecast direction, confidence, and supporting signals
- Includes evaluation and online-training modules for research workflows

### 📰 Time-Aware RAG

> Market news matters differently depending on when it arrives.

- Indexes financial documents and news content
- Retrieves semantically relevant context for a stock or question
- Considers temporal relevance when building market context
- Feeds retrieved information into the chatbot and analysis workflow

### 📐 Technical Indicators

> Read price action through multiple quantitative lenses.

- Relative Strength Index (RSI)
- Moving averages and SMA relationships
- Moving Average Convergence Divergence (MACD)
- Returns, volatility, volume ratios, and event features

### 🛡️ Risk and Portfolio Intelligence

> Understand the risk around a signal before interpreting it.

- Volatility and risk scoring
- Market-regime detection
- Portfolio ranking and recommendation logic
- Context for comparing prediction confidence with market conditions

---

## 🔁 Prediction Workflow

```mermaid
flowchart TD
    A([📊 Stock Price Data]) --> B[📐 Feature Engineering]
    C([📰 Financial News]) --> D[🧠 Sentiment and Event Analysis]
    B --> E[🔗 Feature Fusion]
    D --> E
    E --> F[🕒 Time-Aware RAG Retrieval]
    F --> G[📈 LSTM Forecast Model]
    G --> H[🛡️ Risk and Market Regime Layer]
    H --> I[🖥️ Dashboard, Chat, and Portfolio Views]

    style A fill:#166534,color:#fff,stroke:#15803d
    style C fill:#1e3a5f,color:#fff,stroke:#2563eb
    style E fill:#3b0764,color:#fff,stroke:#7c3aed
    style F fill:#1e1b4b,color:#fff,stroke:#4f46e5
    style G fill:#14532d,color:#fff,stroke:#16a34a
    style H fill:#78350f,color:#fff,stroke:#f59e0b
    style I fill:#0f766e,color:#fff,stroke:#14b8a6
```

---

## 🏗 System Architecture

```mermaid
graph TB
    subgraph CLIENT["🖥️ Next.js Frontend"]
        L[Landing Page]
        D[Dashboard]
        F[Forecast]
        T[Indicators]
        C[AI Chat]
        R[Risk]
    end

    subgraph API["⚙️ FastAPI Backend"]
        S[Stock and Quote APIs]
        P[Prediction APIs]
        N[News and RAG APIs]
        Q[Risk and Portfolio APIs]
    end

    subgraph ML["🧠 Intelligence Layer"]
        I[Technical Indicators]
        E[Event and Sentiment Analysis]
        V[Vector Retrieval]
        M[LSTM Model]
    end

    subgraph DATA["💾 Data Sources"]
        MD[(Market Data)]
        ND[(Financial News)]
        DS[(Processed Datasets)]
    end

    CLIENT --> API
    API --> ML
    ML --> DATA
    DATA --> ML
    ML --> API

    style CLIENT fill:#0f2027,color:#fff,stroke:#10B981
    style API fill:#111827,color:#fff,stroke:#6366f1
    style ML fill:#1e1b4b,color:#fff,stroke:#f59e0b
    style DATA fill:#16324f,color:#fff,stroke:#06b6d4
```

---

## 🧠 Tech Stack

<div align="center">

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js_14-111827?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0EA5E9?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge)

**Backend and Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

**Market Intelligence**

![RAG](https://img.shields.io/badge/RAG-Time--Aware%20Retrieval-7c3aed?style=for-the-badge)
![News](https://img.shields.io/badge/News-Sentiment%20Analysis-0f766e?style=for-the-badge)
![LSTM](https://img.shields.io/badge/Model-LSTM-f59e0b?style=for-the-badge)

</div>

---

## 📁 Folder Structure

```text
Stock_Market_Prediction/
│
├── backend/
│   ├── main.py                    # FastAPI entry point and stock APIs
│   ├── app/api/routes.py          # Application routes
│   ├── data_ingestion/            # Market and news fetchers
│   ├── feature_engineering/       # Model-ready feature creation
│   ├── indicators/                # RSI, MACD, and moving averages
│   ├── models/                    # Neural models and saved LSTM model
│   ├── nlp/                       # Financial NLP and event extraction
│   ├── prediction/                # Training, evaluation, and inference
│   ├── rag/                       # Financial graph and time-aware RAG
│   ├── risk/                      # Risk analysis logic
│   ├── sentiment/                 # Sentiment processing
│   ├── chatbot/                   # Market assistant and retrieval flow
│   ├── data/                      # CSV datasets and processed data
│   └── requirements.txt           # Python dependencies
│
├── frontend/
│   ├── src/app/                   # Next.js pages and dashboard routes
│   ├── src/components/            # Charts, layout, and metric components
│   ├── src/hooks/                 # Data-fetching hooks
│   ├── src/lib/api/               # API client and shared types
│   └── package.json               # Frontend dependencies
│
├── screenshots/                   # README product screenshots
├── HOW_IT_WORKS.md                # Detailed technical explanation
├── docker-compose.yml              # Container orchestration configuration
└── README.md                      # Project documentation
```

---

## 🚀 Installation and Setup

### Prerequisites

| Tool | Version |
| --- | --- |
| Python | 3.10+ |
| Node.js | 18+ |
| npm | 9+ |
| Git | Latest |

### 1. Clone the Repository

```bash
git clone https://github.com/abhishek-ms-01/Stock_Market_Prediction.git
cd Stock_Market_Prediction
```

### 2. Set Up the Backend

```bash
cd backend
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
```

### 3. Configure Environment Variables

```bash
# From the backend directory
copy .env.example .env        # Windows
# cp .env.example .env        # macOS/Linux
```

Add the API credentials required by your selected market and news providers to `backend/.env`. Never commit private keys or tokens.

### 4. Start the Backend

```bash
cd backend
python -m uvicorn main:app --host 0.0.0.0 --port 8000 --reload
```

### 5. Start the Frontend

Open a second terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the live application at **https://www.stockmarketpredictionsystem.site/**. For local development, the dashboard runs at **http://localhost:3000** and the API runs at **http://localhost:8000**.

---

## 📡 Main API Routes

| Method | Route | Purpose |
| :---: | --- | --- |
| `GET` | `/api/stocks` | Available stock symbols and market data |
| `GET` | `/api/stock-data` | Historical stock data and indicators |
| `GET` | `/api/quote/realtime` | Current quote information |
| `GET` | `/api/forecast` | Forecast and directional signal |
| `GET` | `/api/predict` | Prediction output for a selected symbol |
| `POST` | `/api/chat` | RAG-powered market conversation |
| `GET` | `/api/risk` | Risk and market-condition analysis |
| `GET` | `/api/portfolio` | Portfolio guidance and ranking signals |
| `POST` | `/api/train-model` | Trigger model-training workflow |

---

## 📊 Dashboard Modules

<div align="center">

| # | Module | Route | Description |
| :-: | --- | --- | --- |
| 1 | 🏠 Landing | `/` | AlphaTrade introduction and product entry point |
| 2 | 📊 Dashboard | `/dashboard` | Market overview, metrics, and chart context |
| 3 | 🧠 Forecast | `/dashboard/forecast` | Prediction direction and model signals |
| 4 | 📈 Indicators | `/dashboard/indicators` | Technical and sentiment indicators |
| 5 | 🤖 AI Chat | `/dashboard/ai-chat` | Context-aware financial assistant |
| 6 | 🛡️ Risk | `/dashboard/risk` | Risk, regime, and portfolio analysis |
| 7 | ⚡ Live Pipeline | `/dashboard/live-pipeline` | Data-ingestion and processing visibility |

</div>

---

## 🔬 Research Notes

AlphaTrade is intended for educational, research, and dashboard exploration workflows. Forecasts are probabilistic outputs from historical and contextual data. They can be affected by data freshness, market regime changes, news quality, model drift, and unexpected events.

Do not use the application as a substitute for professional financial advice. Validate signals independently and apply appropriate risk management before making investment decisions.

---

## 🔮 Roadmap

<div align="center">

| Status | Planned Improvement |
| :---: | --- |
| 🔜 | Broader real-time market-provider integrations |
| 🔜 | More robust model calibration and uncertainty reporting |
| 🔜 | Expanded event taxonomy for financial news |
| 🔜 | Walk-forward validation and automated model monitoring |
| 🔜 | Portfolio backtesting and scenario analysis |
| 🔜 | Cloud deployment with production observability |

</div>

---

## 🤝 Contributing

Contributions, experiments, and improvements are welcome.

```bash
git checkout -b feature/your-improvement
# make your changes
git add .
git commit -m "feat: describe your improvement"
git push origin feature/your-improvement
```

Then open a pull request with a clear explanation of the change and its validation.

---

## 📄 License

This project is provided for educational and research purposes. Review the repository contents and applicable third-party terms before commercial deployment.

---

## 👨‍💻 Author

<div align="center">

_Full-Stack AI Developer · Market Intelligence Builder_

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-%40abhishek--ms--01-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhishek-ms-01)
&nbsp;&nbsp;
[![Repository](https://img.shields.io/badge/Repository-Stock_Market_Prediction-10B981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhishek-ms-01/Stock_Market_Prediction)

<br/>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=fadeIn"/>

<br/>

**Built with data, models, and market context.**

</div>
