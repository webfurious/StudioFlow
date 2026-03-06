# StudioFlow (Alpha)

Most business tools are either overpriced, overcomplicated, or built for desktops.  
StudioFlow is different.

StudioFlow is a lightweight business management app designed for freelancers, creatives, and small studios who need a simple way to manage clients, projects, invoices, and tasks — without the complexity of enterprise tools.

Built with a focus on clarity, speed, and real-world usability, especially for solo operators who just need things to work.

![StudioFlow Dashboard Preview](https://via.placeholder.com/800x400?text=Dashboard+Preview+%7C+Screenshots+Coming+Soon)  
*(Early mockups of the dashboard, invoice screen, and client list — actual screenshots coming soon)*

## Table of Contents

- [Project Status](#-project-status-)
- [Features](#-features-current-alpha-)
- [Built With](#-built-with-)
- [Design Philosophy](#-design-philosophy-)
- [Data Structure](#-data-structure-current-direction-)
- [Alpha Disclaimer](#-alpha-disclaimer-)
- [Roadmap](#-roadmap-planned-)
- [Contributing / Testing](#-contributing--testing-)
- [Contact & Follow Along](#-contact--follow-along-)
- [Why This Exists](#-why-this-exists-)
- [License](#-license-)

## 🚧 Project Status

StudioFlow is currently in active development (Alpha stage).  
Core systems are functional, but the UI, workflows, and data handling are still being refined before public release.

## ✨ Features (Current / Alpha)

### Client Management
- Create and store client records with contact details and interaction history  
- Fast lookup and minimal-friction search — spend less time scrolling, more time creating

### Project Tracking
- Assign projects to clients and track status, creation date, notes, and updates  
- Simple visual organization (status tags, timelines) to keep everything at a glance

### Invoicing System
- Generate invoices and quotes directly tied to projects  
- Store records securely in Firebase for persistence  
- Structured for upcoming export/email integration (PDF, share links)

### Task Organization
- Manage project-level tasks with lightweight structure  
- No unnecessary complexity — just deadlines, notes, and completion tracking

### User Profile & Settings (In Progress)
- Editable profile and basic app preferences  
- Preparing for future multi-role support (e.g., admin vs. client views)

## 🛠️ Built With

- Java (Android)  
- Firebase Realtime Database  
- Firebase Storage  
- Firebase Authentication  
- Material UI Components  

Originally designed in Sketchware; now transitioning into Android Studio for full control and scalability.

## 📐 Design Philosophy

StudioFlow is intentionally:  
- Not bloated  
- Not overpriced  
- Not trying to be everything  
- Never displaying advertising of any kind  

Instead, it focuses on one thing:  
**Helping small operators run their workflow without fighting their software.**

## 🔒 Data Structure (Current Direction)

Each user owns their own data namespace:
