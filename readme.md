[README.md](https://github.com/user-attachments/files/25938263/README.md)
# 🚴 PedalSafe — Safe Family Bike Route Planner

PedalSafe helps parents find the safest cycling routes when riding with their children. Instead of just finding the fastest route, PedalSafe prioritizes bike paths, low-traffic roads, gentle terrain, and areas with low accident history.

---

## ✨ Features

- **3 Route Alternatives** — Safest, Balanced, and Fastest options ranked by safety score
- **Safety Scoring Engine** — Each route is scored across bike infrastructure, traffic levels, speed limits, terrain, and accident history
- **Accident Zone Overlay** — Visual danger zones displayed on the map (red/orange/yellow)
- **Elevation Profile** — See the hill profile of your route before you ride
- **Address Autocomplete** — Smart address suggestions as you type
- **Export Options** — Open in Google Maps, Apple Maps, RideWithGPS, or download as GPX for Strava
- **100% Free** — Powered by OpenStreetMap and OpenRouteService, no paid API keys needed

---

## 🚀 Getting Started

### 1. Get a Free API Key
Sign up at [openrouteservice.org](https://openrouteservice.org/dev/#/signup) — no credit card required, 2,000 routes/day free.

- Verify your email after signing up (required for the key to activate)
- Copy your API key from the dashboard

### 2. Open the App
Open `pedalsafe.html` in any modern browser, or visit the live version at:
```
https://MGitMoz.github.io/pedalsafe
```

### 3. Activate & Route
1. Paste your ORS API key and click **Activate**
2. Enter a start and end point — addresses auto-populate as you type
3. Select who's riding (baby seat, kids on bikes, cargo bike, etc.)
4. Set your safety priorities using the star ratings
5. Hit **Find Safest Routes** and pick from 3 options

---

## 🛡️ Safety Factors

| Factor | Description |
|---|---|
| 🛤️ Bike paths & trails | Prioritizes dedicated cycling infrastructure |
| 🚦 Low traffic roads | Avoids busy arterials and highways |
| 🐢 Low speed limits | Prefers roads with ≤25 mph speed limits |
| ⛰️ Avoid steep hills | Keeps grades gentle for all ages |
| 🛡️ Low accident history | Routes around collision-prone intersections |

---

## 🗺️ Powered By

- [OpenStreetMap](https://www.openstreetmap.org) — Map tiles and geodata
- [OpenRouteService](https://openrouteservice.org) — Bike-optimized routing engine
- [Leaflet.js](https://leafletjs.com) — Interactive map rendering
- [Nominatim](https://nominatim.org) — Address search and autocomplete

---

## 📁 Project Structure

```
pedalsafe/
├── pedalsafe.html    # Single-file app — everything included
└── README.md
```

---

## 🤝 Contributing

Contributions welcome! Some ideas for future improvements:
- Real accident data integration via city open data APIs
- Saved favorite routes
- Weather overlay (avoid riding in rain)
- Mobile app version

---

## 📄 License

MIT License — free to use, modify, and share.
