# GhumneChalo

An intelligent travel planning Progressive Web Application (PWA) built with Next.js, TypeScript, Tailwind CSS, Prisma, Google Maps Platform, and Gemini AI.

## Features
- **AI Trip Planner**: Dynamic multi-day itinerary generation powered by Gemini AI.
- **Interactive Maps & Navigation**: Directions, route polylines, and discovery via Google Maps Platform.
- **Offline & PWA Support**: Offline trip access, sync, and Web Push notifications.
- **Budget & Expense Tracking**: Categorized expenses, currency tracking, and analytics.
- **Packing Assistant & Emergency Hub**: Smart packing checklists and quick-access emergency contacts.

## Tech Stack
- **Framework**: Next.js (App Router, React 19)
- **Database**: PostgreSQL with Prisma ORM
- **Styling**: Tailwind CSS
- **APIs**: Google Maps JavaScript API, Places API, Routes API, Open-Meteo, Gemini AI

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Set up environment variables:
   Copy `.env.example` to `.env` and fill in your keys:
   ```bash
   cp .env.example .env
   ```

3. Run development server:
   ```bash
   npm run dev
   ```
