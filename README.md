# 🌍 AI Trip Planner

> **AI-powered travel planning application** that generates personalized travel itineraries based on your budget, destination, travel companions, interests, and preferences using **Google Gemini AI**.



---

# 📖 Table of Contents

- Overview
- Features
- Screenshots
- Tech Stack
- Project Architecture
- Folder Structure
- Installation
- Environment Variables
- Running the Project
- Database (Convex)
- AI Integration
- Deployment
- Future Enhancements
- Contributing
- License

---

# ✨ Overview

AI Trip Planner is a modern full-stack web application that helps users generate complete travel plans in seconds using AI.

The application analyzes:

- 📍 Destination
- 💰 Budget
- 👨‍👩‍👧 Number of Travelers
- 🎯 Trip Purpose
- 🍽 Preferences
- 🚫 Restrictions

and generates

- Day-wise itinerary
- Hotels
- Attractions
- Restaurants
- Transportation
- Budget estimation

using **Google Gemini AI**.

---

# 🚀 Features

## 🤖 AI Itinerary Generation

Generate intelligent travel plans using Gemini AI.

✔ Personalized Schedule

✔ Multi-day Planning

✔ Optimized Routes

---

## 💰 Budget Planning

Supports

- Low Budget
- Medium Budget
- Luxury

Includes estimated expenses.

---

## 👨‍👩‍👧 Companion Support

Supports

- Solo
- Couple
- Friends
- Family
- Business Trip

---

## 📍 Google Places Integration

Fetches

- Hotels
- Restaurants
- Tourist Places
- Ratings
- Photos
- Reviews

using Google Places API.

---

## 🗺 Interactive Maps

Built with Leaflet.

Features

- Hotel Location
- Attraction Location
- Route Visualization

---

## 🔐 Authentication

Powered by Clerk

Supports

- Email Login
- Google Login
- Protected Routes

---

## ⚡ Real-Time Database

Powered by Convex

- Store Trips
- Update Trips
- Delete Trips
- Real-time Sync

---

## 🎨 Modern UI

- Tailwind CSS
- shadcn/ui
- Responsive Design
- Mobile Friendly
- Dark Mode Ready

---

# 🖼 Screenshots

```
Home Page

Trip Generator

Generated Itinerary

Trip Details

Map View

Profile Dashboard
```

(Add screenshots here)

---

# 🛠 Tech Stack

## Frontend

- Next.js 15
- React
- TypeScript
- Tailwind CSS
- shadcn/ui

---

## Backend

- Convex

---

## AI

- Google Gemini

---

## Authentication

- Clerk

---

## Security

- Arcjet

---

## Maps

- Leaflet

---

## APIs

- Google Places API

---

# 📂 Project Structure

```
ai-trip-planner/
│
├── app/
│   ├── (auth)
│   ├── dashboard
│   ├── trip
│   ├── api
│   └── layout.tsx
│
├── components/
│   ├── ui
│   ├── trip
│   ├── map
│   └── shared
│
├── convex/
│   ├── schema.ts
│   ├── trips.ts
│   ├── users.ts
│   └── _generated
│
├── lib/
│
├── hooks/
│
├── public/
│
├── styles/
│
├── utils/
│
├── .env.local
│
├── package.json
│
└── README.md
```

---

# ⚙ Installation

Clone repository

```bash
git clone https://github.com/suryaprakashgowda/ai-trip-planner.git
```

Go to project

```bash
cd ai-trip-planner
```

Install dependencies

```bash
npm install
```

or

```bash
yarn
```

---

# 🔑 Environment Variables

Create

```
.env.local
```

Add

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/

NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Convex
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Gemini
GEMINI_API_KEY=

# Arcjet
ARCJET_KEY=

# Google Places
GOOGLE_PLACE_API_KEY=
```

---

# ▶ Running the Project

Start Convex

```bash
npx convex dev
```

Start Next.js

```bash
npm run dev
```

Application

```
http://localhost:3000
```

---

# 🗄 Convex Database

Generate schema

```bash
npx convex dev
```

Deploy

```bash
npx convex deploy
```

Dashboard

```
https://dashboard.convex.dev
```

---

# 🤖 AI Workflow

```
User Input
      │
      ▼
Travel Preferences
      │
      ▼
Gemini AI
      │
      ▼
Generated JSON
      │
      ▼
Store in Convex
      │
      ▼
Display Trip
```

---

# 🌍 Google Places Workflow

```
Destination
      │
      ▼
Google Places API
      │
      ▼
Hotels

Restaurants

Tourist Attractions

Ratings

Photos
```

---

# 🚀 Deployment

Deploy to **Vercel**

```bash
vercel
```

or connect GitHub repository with Vercel.

Add all environment variables before deployment.

---

# 📈 Future Enhancements

- AI Chat Assistant
- Offline Mode
- Voice Assistant
- Weather Forecast
- Flight Booking
- Hotel Booking
- Expense Tracking
- Multi-language Support
- Travel History
- PDF Export
- Share Trip
- Travel Recommendations
- Budget Analytics

---

# 🤝 Contributing

Contributions are always welcome.

1. Fork the repository

2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Open Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Your Name**

GitHub:
https://github.com/suryaprakashgowda

LinkedIn:
https://linkedin.com/in/suryaprakashgowda

Portfolio:
https://surya-pystack-portfolio.vercel.app/

---

# ⭐ Support

If you like this project,

⭐ Star this repository

🍴 Fork it

📢 Share it with others.

---

<p align="center">
Made with ❤️ using Next.js, Convex, Gemini AI, Clerk & Google Places API
</p>
