MyFoodMatrix


A cross-platform mobile application (iOS, Android, web) designed to empower health-conscious users to log meals, track nutritional quality, ensure diet and allergen compliance, generate personalized recipes, and monitor wellness goals through AI-driven insights. The app offers free and premium tiers to cater to diverse user needs.
Overview

Objective: Simplify nutrition tracking and meal planning for individuals with dietary preferences (e.g., keto, vegan, gluten-free) or allergies, using photo/text/voice inputs and AI-powered analysis.
Platforms: iOS, Android (React Native), Web (Tailwind CSS).
Key Features:
Photo/text-based meal logging with OCR and NLP.
Smart nutrition, diet compatibility, and allergen safety scores.
Personalized recipe generation with nutritional breakdowns.
Daily wellness tracking with gamification.



Documentation

Product Requirements Document (PRD): Detailed requirements, features, and roadmap.
API Specification: OpenAPI specs for backend endpoints.
Architecture Diagram: High-level system design.

Getting Started
Prerequisites

Node.js v18+ and npm
React Native CLI
Supabase account for database setup
API keys for Open Food Facts and USDA FoodData Central

Installation

Clone the repository:git clone https://github.com/your-username/MyFoodMatrix.git
cd MyFoodMatrix


Install frontend dependencies:cd src/frontend
npm install


Install backend dependencies:cd src/backend
npm install


Configure environment variables:
Copy .env.example to .env in src/frontend and src/backend.
Add API keys and Supabase credentials.


Start the development server:
Frontend: npm start (React Native).
Backend: npm run dev (Node.js/Express).



See Frontend README and Backend README for detailed setup.
Project Structure
MyFoodMatrix/
├── docs/                    # Documentation
│   ├── MyFoodMatrix_PRD.md  # Product Requirements Document
│   ├── assets/              # Diagrams and images
│   ├── api/                 # API specifications
├── src/                     # Source code
│   ├── frontend/            # React Native app
│   ├── backend/             # Node.js/Express server
├── .github/                 # GitHub Actions workflows
├── README.md                # Project overview
├── CONTRIBUTING.md          # Contribution guidelines
├── LICENSE                  # License file
├── .gitignore               # Ignored files

Contributing
Contributions are welcome! Please read CONTRIBUTING.md for guidelines on:

Submitting PRD updates or feature proposals.
Writing code and tests.
Reporting issues or bugs.

Use GitHub Issues to track feedback or suggestions, and tag them with prd, frontend, or backend.
License
This project is licensed under the MIT License.
Contact
For questions or support, contact the product manager at [your-email@example.com] or open an issue on GitHub.
