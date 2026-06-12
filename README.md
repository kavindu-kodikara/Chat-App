# Chat App Practical Project

This repository contains the Expo React Native frontend for the Chat App practical project created for the HDP 1 subject at Java Institute for Advanced Technology.

It is intended as a reference for BSc Hons Software Engineering second-year students. If you miss a class or practical coding session, you can review the daily commit history by lecture day (for example: `Day - 28`, `Day - 29`).

## About this project

- Platform: Expo React Native
- Purpose: Chat App frontend for practical class work
- Audience: BSc Hons Software Engineering 2nd year students
- Institute: Java Institute for Advanced Technology
- Website: <https://www.javainstitute.edu.lk/>

## How to use this repository

### Clone the repository

If you have Git installed, use:

```bash
git clone <repository-url>
cd Chat-App
```

Replace `<repository-url>` with the repository URL provided by your lecturer or hosting platform.

### Download as ZIP

If you do not want to use Git, download the project as a ZIP from the repository hosting website, extract it, then open the extracted folder in your terminal.

### Find the day you missed

Each commit is labeled with the lecture day, for example:

- `Day - 28`
- `Day - 29`
- `Day - 30`

Use commit history or the hosting platform’s history view to locate the code for the lecture day you missed.

## Setup and run

Install dependencies:

```bash
npm install
```

Start the Expo development server:

```bash
npx expo start
```

Then choose one of these options:

- Open on Android emulator
- Open on iOS simulator
- Open in Expo Go on a physical device

## Project structure

- `app/` — main application screens and route-based pages
- `components/` — reusable UI components
- `constants/` — theme and shared constants
- `hooks/` — custom React hooks
- `assets/` — images and asset files
- `scripts/` — helper scripts
- `package.json` — project scripts and dependencies

## Useful commands

- `npm install` — install dependencies
- `npx expo start` — start Expo development server
- `npm run android` — run on Android emulator/device
- `npm run ios` — run on iOS simulator
- `npm run web` — run web version
- `npm run lint` — lint the project

## Student instructions

If you miss practical code in class:

1. Check the daily commit messages, which are named by lecture day.
2. Open the commit history in Git or on the repository hosting platform.
3. Review the specific day’s code changes.
4. Run `npm install` and `npx expo start` to test the project locally.

## Lecturer notes

- Keep commit messages consistent with the day labels.
- Encourage students to use this repo as a reference only after trying the tasks themselves.
- Use daily commit history to help students catch up quickly.

---

For more information about Java Institute for Advanced Technology, visit <https://www.javainstitute.edu.lk/>.
