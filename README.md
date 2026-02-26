# EcoPulse AI - Real-Time Environmental Intelligence

EcoPulse AI is a production-grade, smart-city intelligence system that monitors environmental health in real-time. By leveraging Kafka for high-throughput data streaming and Pathway's incremental processing engine, the platform delivers immediate insights into air quality, forecasting, and anomaly detection.

## 🏗 Architecture
- **Kafka**: Simulated environmental sensor stream for high-velocity data.
- **Pathway**: High-performance streaming engine for feature engineering and real-time anomaly detection.
- **Flask**: Enterprise-grade API and multi-page UI.
- **Climate Copilot & Operational Planner**: LLM-powered scientific advisor and city operations strategist.

## 🚀 Getting Started

1. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Ensure Kafka is Running**:
   The system expects a Kafka broker at `localhost:9092`.

3. **Set OpenAI API Key**:
   Create a `.env` file with `OPENAI_API_KEY=your_key`.

4. **Run the System**:
   ```bash
   python main.py
   ```

## 🌐 Features
- **Live Dashboard**: Real-time monitoring of AQI, PM2.5, and CO2.
- **Smart Daily Action Plan**: AI-driven operational plans (Today's Air Action Plan) with condition-based protocols.
- **Advanced Analytics**: Momentum and volatility tracking using Pathway's streaming capabilities.
- **Climate Copilot**: Interactive AI assistant for deep environmental insights.
- **Incident Reports**: Detailed historical logs and automated briefing generation.

## 🛠 Tech Stack
- **Streaming Engine**: Pathway
- **Message Broker**: Kafka
- **Web Framework**: Flask
- **Styling**: TailwindCSS, CSS3
- **Visuals**: Chart.js, Leaflet.js
- **Intelligence**: OpenAI GPT-4o
