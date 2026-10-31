# My Monthly Budget
Responsive personal budget tracker using Firebase Authentication and Cloud Firestore.

## Firebase setup
- Copy the Firebase web app `firebaseConfig` values into `firebase-config.js`.
- In Firestore > Rules, publish the contents of `firestore.rules`.
- In Authentication > Settings > Authorized domains, add your Cloudflare Pages domain after deployment.

## Deploy
Static website. Cloudflare Pages build command: leave blank. Build output directory: `/` or `.` as accepted by the dashboard.

## First login
Enter your email and a strong password (at least 6 characters), then select Create account.

Currency is PHP. Savings deposits are separate from expenses. Available balance = income - expenses - savings deposits. Never publish Firebase service-account private keys.
