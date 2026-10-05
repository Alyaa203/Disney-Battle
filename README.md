<div align="center">

# Disney Battle ⚔️

**A multiplayer card battle game with Disney characters, built for mobile.**

![React](https://img.shields.io/badge/React_19-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)

</div>

> **Note:** this repository is the **starting point** of the project: the React + Vite setup and folder structure. The finished game, renamed **Smash Princes**, is in **[Alyaa203/d-veloppement-mobile](https://github.com/Alyaa203/d-veloppement-mobile)** and can be played at **[smash-princes.netlify.app](https://smash-princes.netlify.app)**.

---

## Overview

Disney Battle is a turn-based card game in which two players build a deck of Disney characters and fight each other in real time, each on their own phone.

**Why it exists:** it is a team mobile development project at ENSC (Bordeaux INP). The aim was to build a complete web app: an external REST API, sign-in, real-time sync between two devices, deployment and user testing.

---

## Features

This repository sets up the base of the app:

- React 19 + Vite project with ESLint
- Folder structure for the app: `pages/` (screens), `components/` (reusable UI) and `services/` (API and back-end calls)
- First page placeholder (`loginPage`)

Features of the finished game ([see the final repo](https://github.com/Alyaa203/d-veloppement-mobile)):

- Google sign-in with Firebase
- Deck builder using characters from the [Disney API](https://disneyapi.dev)
- Lobby to create or join a game
- Real-time turn-based combat synced with Firebase Realtime Database

---

## Tech stack

| Area | Tools |
| --- | --- |
| Front end | React 19, Vite |
| Code quality | ESLint |
| Added in the final version | Firebase (Auth + Realtime Database), Material UI, React Router, Netlify |

---

## Getting started

Requires [Node.js](https://nodejs.org/) 20 or later.

```bash
git clone https://github.com/Alyaa203/Disney-Battle.git
cd Disney-Battle
npm install
npm run dev      # dev server at http://localhost:5173
```

Other commands:

```bash
npm run build    # production build in dist/
npm run preview  # preview the production build
npm run lint     # ESLint
```

---

## Screenshots

> _Screenshots coming soon._

| Login | Deck builder | Battle |
| :---: | :---: | :---: |
| ![Login](docs/screenshots/login.png) | ![Deck builder](docs/screenshots/deck.png) | ![Battle](docs/screenshots/battle.png) |

<!-- Add images to docs/screenshots/ using the file names above. -->

---

**Team project** at ENSC (Bordeaux INP) by Alyaa Saab and Lucas Sainte-Croix.
