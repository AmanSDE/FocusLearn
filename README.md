# FocusLearn 📚🎥🔊
**Your All-in-One Learning Productivity Platform**  
*"Read, Watch, Reflect, and Grow – All in One Space."*

<div align="center">
  <img src="https://github.com/AmanSDE/FocusLearn/blob/main/assets/hero-animation.gif?raw=true" alt="FocusLearn Demo" width="800">
  
  [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
  [![GitHub Stars](https://img.shields.io/github/stars/AmanSDE/FocusLearn?style=social)](https://github.com/AmanSDE/FocusLearn/stargazers)
</div>

## 🌟 Why FocusLearn?

<div align="center">
  <img src="https://github.com/AmanSDE/FocusLearn/blob/main/assets/problem-solution.png?raw=true" alt="Problem vs Solution" width="600">
</div>

Modern learners juggle between multiple tools:
- 📚 PDF readers
- 🎬 Video players
- 📝 Note-taking apps
- ⏱️ Time trackers
- 🎧 Focus tools

**FocusLearn consolidates everything into one powerful platform:**
    title Learning Tool Consolidation
    "FocusLearn" : 85
    "Other Tools" : 15
🚀 Key Features
📚 Unified Learning Hub
PDF Reader with pagination and bookmarks

YouTube Integration with progress tracking

Seamless Switching between media types

✍️ Smart Annotation System
![sequenceDiagram_20250420_83418c](https://github.com/user-attachments/assets/35209abd-ab4d-4da5-9cd6-ce56d91dae6c)

📊 Progress Analytics
Metric	Description
⏱️ Time Spent	Track learning sessions
📈 Completion	Visualize progress
🎯 Goals	Set and achieve targets
🔇 Focus Environment

White noise generator (6 presets)

Full-screen distraction-free mode

Pomodoro timer with breaks

🛠️ Technology Stack
Layer	 Technologies  	Purpose
Frontend	Angular 16, PrimeNG, RxJS	Responsive UI
Backend	.NET 7, MongoDB	API & Data
DevOps	Docker, GitHub Actions	CI/CD Pipeline


sequenceDiagram
    User->>FocusLearn: Adds note at timestamp
    FocusLearn->>Database: Stores note with metadata
    Database-->>FocusLearn: Confirms storage
    FocusLearn-->>User: Displays saved note

🏗️ Architecture Overview
![Architecture](https://github.com/user-attachments/assets/d907344b-d43f-4576-b88e-7bbbfc0cdeef)

📦 Installation Guide
Prerequisites
# Required Tools
npm install -g @angular/cli
dotnet tool install -g dotnet-ef
docker --version

# 1. Clone repository
git clone https://github.com/AmanSDE/FocusLearn.git
# Quick Start
# 2. Run with Docker
cd FocusLearn
docker-compose up --build
#Configuration
.env.example
MONGODB_URI=mongodb://mongo:27017/focuslearn
JWT_SECRET=your_secure_key

🧩 Project Structure
FocusLearn/
├── client-app/          # Angular Frontend
│   ├── src/
│   │   ├── app/
│   │   │   ├── core/       # Services
│   │   │   ├── modules/    # Feature modules
│   │   │   └── shared/     # Components
├── server-api/         # .NET Backend
│   ├── Application/    # Business logic
│   ├── Domain/         # Models
│   └── Infrastructure/ # Data access
├── docs/              # Architecture diagrams
└── tests/             # Unit & integration tests

🤝 Contributing
<div align="center"> <img src="https://github.com/AmanSDE/FocusLearn/blob/main/assets/contributing-flow.png?raw=true" alt="Contributing Flow" width="600"> </div>
Fork the repository

Create your feature branch (git checkout -b feat/amazing-feature)

Commit your changes (git commit -m 'Add some amazing feature')

Push to the branch (git push origin feat/amazing-feature)

Open a Pull Request

Coding Standards:

Follow Angular Style Guide

Use Clean Architecture principles

Maintain 80%+ test coverage

Document new features

📜 License
Distributed under the MIT License. See LICENSE for more information.

📬 Contact
Aman Shahi - @AmanSDE - am.amanshahi@example.com

Project Link: https://github.com/AmanSDE/FocusLearn

<div align="center"> <h3>🌟 Star us on GitHub if you find this project useful! 🌟</h3> <p>Help us build the future of focused learning</p> </div> 


