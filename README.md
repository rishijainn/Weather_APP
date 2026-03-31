# Weather Dashboard 🌦️

A sleek, responsive, and performance-driven **Weather Dashboard** built with **React**, **Vite**, and **TypeScript**. This application provides real-time weather updates, interactive maps, and detailed forecasts using high-performance Edge functions on Vercel.

---

## 👨‍💻 Author

**Rishi Jain**

---

## 🚀 Features

* **Real-Time Geolocation**
  Automatically detects your current location via Vercel Edge Headers for instant local weather.

* **Interactive Maps**
  Full MapLibre GL integration with a modern "Alidade Smooth Dark" UI from Stadia Maps.

* **Smart Forecasts**
  24-hour hourly trends and sunrise/sunset tracking.

* **Edge-Powered Backend**
  Custom Vercel Edge functions bypass CORS issues and provide lightning-fast data fetching.

* **Responsive Bento UI**
  A modern, high-contrast dashboard layout optimized for all screen sizes.

---

## 🛠️ Tech Stack

* **Frontend**: React (Vite), TypeScript, Tailwind CSS
* **Map Engine**: MapLibre GL JS
* **API Providers**: Visual Crossing (Weather), Stadia Maps (Tiles), Nominatim (Geocoding)
* **Deployment**: Vercel (Edge Functions & Hosting)

---

## 📦 Installation

```bash
git clone https://github.com/rishijainn/Weather_APP.git
cd Weather_APP
npm install
```

Create a `.env` file and add your API keys:

```env
VITE_WEATHER_API_KEY=your_key_here
VITE_STADIA_API_KEY=your_key_here
```

Run the development server:

```bash
npm run dev
```

---

## ☁️ Deployment

This project is optimized for **Vercel**.

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add the following environment variables in Vercel:

   * `VITE_WEATHER_API_KEY`
   * `VITE_STADIA_API_KEY`
4. Vercel will automatically detect the `/api` folder and deploy Edge functions

---

## ⭐ Support

If you like this project, consider giving it a star ⭐ on GitHub!
