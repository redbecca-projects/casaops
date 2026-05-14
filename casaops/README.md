# CasaOps

Spanish-first Airbnb operations app prototype.

## Use locally
1. Install Node.js
2. Open this folder in Terminal
3. Run: `npm install`
4. Run: `npm run dev`
5. Open the local link shown in the terminal

## Deploy free on Vercel
1. Create a free Vercel account
2. Create a free GitHub account
3. Upload this folder to a GitHub repo
4. In Vercel, click New Project and import the repo
5. Framework: Vite
6. Build command: `npm run build`
7. Output directory: `dist`

## Firebase setup
Create Firebase project, add a Web App, then paste config into `src/firebase.js`.

This version is a front-end working prototype. Database, login, and real photo upload are prepared for Firebase but not active until config is added and Firestore/Storage code is connected.
