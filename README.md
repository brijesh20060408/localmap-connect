# localmap-connect
A mobile spatial infrastructure reporting platform integrating Leaflet.js mapping, PostGIS spatial queries, and automated AI categorization.
# 🗺️ LocalMap Connect

> A crowdsourced spatial infrastructure reporting platform designed for urban maintenance, field data collection, and automated issue classification.

![LocalMap Connect Interface](https://via.placeholder.com/1200x600?text=LocalMap+Connect+Dashboard+Screenshot)

## ✨ Key Features

- 📍 **Interactive Spatial Mapping:** Interactive Leaflet.js web map supporting coordinate pinning, custom severity markers, and GeoJSON feeds.
- 🤖 **Automated AI Categorization:** Natural language processing via Google Gemini SDK to classify infrastructure hazards and assign estimated SLA turnaround times.
- 🗺️ **PostGIS Spatial Database:** Spatial query indexing and storage built on PostgreSQL and PostGIS.
- 📊 **Real-time Analytics:** Interactive metrics, severity histograms, and sector distribution charts using Chart.js.
- 📱 **Mobile & Field Ready:** Optimized layout suitable for mobile browser field reporting and QField spatial integration.

---

## 🛠️ Tech Stack

- **Frontend:** Single-page HTML5/JS dashboard, Leaflet.js, Chart.js, Tailwind CSS
- **Backend:** Python 3.10+, FastAPI, SQLAlchemy, GeoAlchemy2
- **Database:** PostgreSQL with PostGIS extension
- **AI & Messaging:** Google Gemini API, WhatsApp Cloud API
- **DevOps:** Docker, Docker Compose, Alembic, Pytest

---

## 🚀 Quick Start (Local Development)

### Prerequisites
- Docker & Docker Compose installed

### Execution Steps
```bash
# 1. Clone the repository
git clone [https://github.com/YOUR_USERNAME/localmap-connect.git](https://github.com/YOUR_USERNAME/localmap-connect.git)
cd localmap-connect

# 2. Configure environment variables
cp .env.example .env

# 3. Launch the containerized application
docker-compose up --build
```

Access the live interface at `http://localhost:8000`.

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
