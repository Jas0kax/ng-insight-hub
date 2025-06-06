# 📈 ng-insight-hub

**ng-insight-hub** is a real-time performance monitoring tool for Angular applications. It visualizes metrics like rendering time, change detection cycles, and HTTP call delays across environments, helping developers identify and resolve performance bottlenecks quickly.

Designed to integrate seamlessly via a lightweight SDK, it enables distributed observability for Angular-based platforms with minimal overhead.

## 📌 Features

- 🚦 **Live App Telemetry**:
  - Tracks FPS, zone stability, and rendering delays
  - HTTP call duration charts and detection cycles by component

- 🧩 **SDK-Based Integration**:
  - Lightweight client-side plugin for Angular apps
  - Centralized metrics ingestion via WebSocket or REST

- 📉 **Developer Dashboards**:
  - Environment-based filters (dev, staging, prod)
  - Historical performance charts and trendlines

## 🧰 Tech Stack

- **Frontend**: Angular, Chart.js, WebSocket
- **SDK**: Angular library (insight-hub-sdk)
- **Backend**: Node.js, Redis, InfluxDB (optional)
- **Deployment**: Docker, Netlify, or AWS Amplify

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/ng-insight-hub.git
cd ng-insight-hub
npm install
ng serve
