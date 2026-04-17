# CHONO Expo Mobile App

CHONO is a minimalist, industrial React Native (Expo) application foundation for construction auditing.

## Stack

- Expo + React Native + TypeScript
- Clerk (`@clerk/clerk-expo`) for auth with OAuth providers
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

3. Add your Clerk publishable key in `.env`:

   ```bash
   EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_live_or_test_key_here
   ```

4. In Clerk Dashboard, configure Google and Facebook OAuth for the application.

5. Start Expo:

   ```bash
   npm run start
   ```

## Implemented Foundation

- Branded login screen with Google/Facebook OAuth actions
- Clerk provider and secure token caching via `expo-secure-store`
- Auth gate routing between Login and Drawer app
- Hero Dashboard with 4 Mongolian action cards
- Profile scaffold with editable fields and Save/Edit toggle
- Light/dark adaptive theme tokens

## Notes

- New Clerk OAuth users are automatically provisioned on first successful sign-in.
- Replace the temporary wolf logo image URI with your local CHONO brand asset in `assets` when available.
# ChonoPhone
