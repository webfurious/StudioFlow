Studio Flow (Alpha)
Studio Flow is a lightweight business management app designed for freelancers, creatives, and small studios who need a simple way to manage clients, projects, invoices, and tasks — without the complexity of enterprise tools.
This app is being built with a focus on clarity, speed, and real-world usability, especially for solo operators who just need things to work.

🚧 Project Status
Studio Flow is currently in active development (Alpha Stage).
Core systems are functional, but the UI, workflows, and data handling are still being refined before public release.

✨ Features (Current)
Client Management
    • Create and store client records
    • Track contact details and history
    • Designed for fast lookup and minimal friction
Project Tracking
    • Assign projects to clients
    • Track status, creation date, and updates
    • Built for simple, visual organization
Invoicing System
    • Generate invoices and Quotes tied to projects
    • Store invoice records locally in database
    • Structured for future export/email integration
Task Organization
    • Manage project-level tasks
    • Lightweight structure without unnecessary complexity
User Profile & Settings (In Progress)
    • Editable user profile
    • App configuration and preferences
    • Preparing for future multi-role support

🛠️ Built With
    • Java (Android)
    • Firebase Realtime Database
    • Firebase Storage
    • FirebaseAuth
    • Material UI Components
    • Designed originally in Sketchware, now being transitioned into Android Studio for full control and scalability.

📐 Design Philosophy
StudioFlow is intentionally:
    • Not bloated
    • Not Overpriced
    • Not trying to be everything
    • Not going to EVER display any kind of advertising in the App
Instead, it focuses on:
«Helping small operators run their workflow without fighting their software.»

🔒 Data Structure (Current Direction)
Each user owns their own data namespace:
uid/ ├── userProfile/ ├── clients/ ├── projects/ ├── invoices/ └── appSettings/
This ensures:
    • Clean separation between users
    • Simple Firebase security rules
    • Easy scaling later

⚠️ Alpha Disclaimer
This is not production software yet.
Expect:
    • UI changes
    • Database structure adjustments
    • Feature reshaping
    • Occasional bugs
The goal right now is stability first, polish second.

📌 Roadmap (Planned)
    • Improved dashboard overview
    • Safer data validation
    • Export/share invoice capability
    • Role-based access (Admin / Client view)
    • Cloud sync hardening
    • UI consistency pass
    • Closed beta release

🤝 Contributing / Testing
Alpha testing will open to a limited number of users once stability milestones are met.
If you're interested in testing or providing feedback, reach out when announcements are made.

🧠 Why This Exists
Studio Flow is being built from the ground up to solve a real problem:
Modern tools are either too expensive, too complex, or too disconnected from how freelancers actually work.
This app is about reclaiming that middle ground.

License
Currently private during development. Licensing will be determined before public release.

More updates coming as development continues.
