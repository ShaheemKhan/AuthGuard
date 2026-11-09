# AuthGuard

AuthGuard is a React Native two-factor authentication app for generating and managing time-based one-time passwords (TOTP).

## Overview
Users can add accounts by scanning QR codes, view rotating 6-digit codes, copy them quickly, and organize tokens with icons, labels, and folders.

## Problem
Users need a secure, offline-friendly way to manage MFA codes without switching between multiple apps.

## Solution
AuthGuard provides a fast, privacy-focused authenticator with secure local storage and optional encrypted backup.

## Features
- QR-code account setup
- TOTP code generation
- Code copy and countdown timer
- Account search and grouping
- Biometric unlock
- Encrypted local backup

## Tech Stack
- React Native + Expo
- TypeScript
- expo-camera
- react-native-keychain / SecureStore
- TOTP generation logic
- Biometrics via native module

## Next Steps
- Add additional code formats
- Add encrypted cloud backup
- Improve QR scanning reliability
- Add Apple Watch code companion
- Add account import/export with strong encryption
