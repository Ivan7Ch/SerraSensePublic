# SerraSense

**SerraSense** is an iOS app for real-time greenhouse monitoring. Connect it to your own IoT server and get instant readings from all your sensors — no cloud subscriptions, no middlemen.

---

## Features

- **Live sensor data** — air temperature, humidity, soil moisture, and atmospheric pressure
- **Two locations** — separate views for greenhouse and outdoor sensors
- **Climate intelligence** — automatic VPD (plant comfort) and dew point margin (condensation risk) calculations
- **Analytics** — day / week / month charts for any sensor with min, avg, and max stats
- **Local connection** — connects directly to your server via IP and port

## Requirements

- iPhone running iOS 17+
- A local server exposing sensor data via HTTP

## API

The app expects the following endpoints on your server:
