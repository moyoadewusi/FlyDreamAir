# FlyDreamAir Loyalty Program Web App

A web application that simulates a loyalty program where users can log in, earn points, redeem rewards, view their redemption history, and undo redemptions. This project was built as a part of a university group assignment.

## Features

- User Authentication (Simple frontend simulation)
- Profile View with Real-Time Points Display
- Rewards Redemption with Undo Capability
- Points History Log
- Dark Mode Based on System Preferences
- Fully Responsive UI (Mobile, Tablet, Desktop)

## How It Works

1. **Account**: The user can "delete account" which will reset actions recorded in localStorage.
2. **Navigation**: The navbar allows switching between sections.
3. **Points**: Users earn points and can redeem them for flights and hotel reservations.
4. **History**: All earning and redemptions actions are recorded in localStorage.
5. **Levels**: As points are earned, the account level/tier will increase. Allowing for new options for redemption.

## Technologies Used

- HTML5 & CSS3
- JavaScript (ES6+)
- LocalStorage API
- Responsive Design (Flexbox, Media Queries)
- Dark Mode with `prefers-color-scheme`
