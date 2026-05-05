# CHONO Expo Mobile App

CHONO is a minimalist, industrial React Native (Expo) application foundation for construction auditing.

## Stack

- Expo + React Native + TypeScript
- Local in-app auth context (no external auth provider)
- React Navigation (Stack + Drawer)
- NativeWind (Tailwind utility classes)
- Icons: Lucide + MaterialCommunityIcons

## Setup

1. Install dependencies:

   ```bash
   npm install
   ```

2. Create your local environment file:

   ```bash
   cp .env.example .env
   ```

3. Start Expo:

   ```bash
   npm run start
   ```

## Implemented Foundation

- Branded login screen with local demo login
- Auth gate routing between Login and tab app
- Hero Dashboard with 4 Mongolian action cards
- Profile scaffold with editable fields and Save/Edit toggle
- Light/dark adaptive theme tokens
- News and Projects screens aligned to CHONO references
- Branded splash animation sequence

## Notes

- Local auth is currently in-memory for demo UI flow (replace with API auth when backend is ready).
# ChonoPhone
# buildingPhone
# chonoPhones
