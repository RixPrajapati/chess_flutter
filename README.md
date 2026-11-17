# ♟️ Chess Coach AI Mobile

**A Flutter-Based Mobile Companion for Personalised Chess Training**

Chess Coach AI Mobile is a Flutter-based Android application designed to help amateur chess players understand their mistakes, identify recurring weaknesses and improve their chess skills through personalised training.

The application analyses imported chess games using Stockfish and converts complex engine evaluations into simple, understandable coaching feedback.

## 🎯 Project Overview

Many amateur chess players struggle to understand why they lose games. Although chess engines provide accurate evaluations, their numerical scores and analysis can be difficult for beginners to interpret.

Chess Coach AI Mobile addresses this problem by analysing multiple games, identifying recurring mistakes and providing personalised recommendations to help players improve.

**Target Users:** Amateur chess players rated approximately 800–1600 Elo.

## ✨ Key Features

- **User Authentication:** Secure sign-up and sign-in with JWT authentication.
- **Chess Dashboard:** View rating, playing performance, progress trends and weaknesses.
- **PGN Import:** Import single or multiple chess games using PGN files.
- **Game Analysis:** Analyse chess games using the Stockfish engine.
- **Mistake Detection:** Identify blunders, mistakes and inaccuracies.
- **Personalised Coaching:** Receive short explanations of important mistakes.
- **Opening Repertoire:** Track win, draw and loss statistics for different openings.
- **Daily Training Plan:** Get exercises based on identified weaknesses.
- **Progress Tracking:** Monitor improvement through training activity and performance statistics.

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Mobile Development | Flutter |
| Programming Language | Dart |
| Backend | Node.js |
| Backend Framework | Express.js |
| Database | MongoDB |
| Chess Engine | Stockfish |
| API Communication | REST API |
| Authentication | JSON Web Token (JWT) |
| Architecture | MVVM |
| State Management | Provider |
| Version Control | Git & GitHub |
| UI/UX Design | Figma |

## 🏗️ Application Architecture

The application follows the **Model-View-ViewModel (MVVM)** architectural pattern.

- **Model:** Handles application data and business rules.
- **View:** Displays the user interface and interacts with users.
- **ViewModel:** Manages UI state and communicates with repositories.
- **Repository:** Handles communication with the backend API and local cache.

The backend handles chess game analysis and communicates with the Stockfish engine.

## 📱 Main Application Screens

1. Sign In / Sign Up
2. Home Dashboard
3. Chess Game Analysis
4. Opening Repertoire
5. Daily Training Plan
6. User Profile

## 🌿 Git Branching Strategy

This project follows a structured Git branching strategy:

| Branch | Purpose |
|---|---|
| `main` | Stable and release-ready code |
| `develop` | Main development and integration branch |
| `feature/*` | Development of individual application features |

Feature branches are created from `develop` and merged back through Pull Requests after implementation and testing.

## 📂 Project Scope

### Included in Scope
- Android mobile application
- User authentication
- PGN game import
- Chess game analysis
- Recurring weakness identification
- Opening repertoire statistics
- Personalised daily training

### Outside Initial Scope
- Live multiplayer chess
- In-app payments
- Initial iOS release

## 🚀 Project Status

**Status:** Planning and Development

This project is being developed as part of the Mobile Application Development module (ST6002CEM) at Softwarica College of IT and E-Commerce in collaboration with Coventry University.

## 👨‍💻 Author

**Rix Prajapati**

- GitHub: [@RixPrajapati](https://github.com/RixPrajapati)

## 📄 License

This repository is maintained for academic project and educational purposes.
