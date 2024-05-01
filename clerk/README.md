# React Native Authentication with Clerk and Expo Router

Check out the full [video tutorial](https://www.youtube.com/watch?v=zh6Sc1flK2g) and also [the written tutorial](https://galaxies.dev/react-native-authentication-clerk)!

Use [Clerk](https://clerk.com/?utm_source=sponsorship&utm_medium=video&utm_campaign=simong&utm_content=08_15_2023) for epic user management 🔥

## 🚀 How to use

```sh
npx expo
```

## 📝 Notes

- [Expo Router: Docs](https://expo.github.io/router)
- [Expo Router: Repo](https://github.com/expo/router)

## Updating Clerk Secret Key

To update the Clerk secret key used in this project, follow these steps:

1. Navigate to the `app/_layout.tsx` file in your project directory.
2. Locate the section where the ClerkProvider is initialized.
3. Replace the `const CLERK_PUBLISHABLE_KEY` with your actual Clerk frontend API key.

Example:

```tsx
import { ClerkProvider } from '@clerk/clerk-react';

const CLERK_PUBLISHABLE_KEY = 'YOUR_CLERK_FRONTEND_API_KEY';

<ClerkProvider frontendApi={CLERK_PUBLISHABLE_KEY}>
