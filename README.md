# 📱 MyFoodMatrix – AI-Powered Nutrition & Wellness Tracker

MyFoodMatrix is a cutting-edge, cross-platform mobile application (iOS, Android, and web) designed to empower health-conscious users to manage their nutrition and wellness effectively. Leveraging advanced AI-driven insights, the app enables meal logging, nutritional analysis, diet/allergen compliance, personalized recipe generation, and goal tracking. Available in free and premium tiers ($9.99/month or $99.99/year), it caters to fitness enthusiasts, home cooks, and individuals with dietary restrictions.

---

## 🌟 Project Highlights

- **Purpose:** Simplify nutrition tracking and meal planning for healthy lifestyles, dietary preferences (e.g., keto, vegan, gluten-free), and allergen management.
- **Target Audience:** Adults (18–65), fitness enthusiasts, home cooks, dieticians, and health coaches.
- **Key Value Proposition:**
  - **Convenience:** Quick meal logging via photo, text, or voice.
  - **Personalization:** Tailored recipes and insights based on user preferences.
  - **Transparency:** Detailed scoring for nutrition, allergens, and sustainability.
  - **Engagement:** Gamified wellness tracking with actionable feedback.

---

## 📋 Features Overview

| Feature             | Description                                                                                  | Availability    |
|---------------------|----------------------------------------------------------------------------------------------|-----------------|
| **Photo/Text Logging**     | Log meals with photos (JPG/PNG) or text using OCR (Tesseract.js) and NLP (DistilBERT).       | Free            |
| **Nutrition Score**        | 0–100 score (A–D) based on macronutrients, micronutrients, and penalties for sugar/trans fats. | Free            |
| **Diet Compatibility**     | Yes/No flags for keto, vegan, gluten-free diets; premium offers percentage match and alternatives. | Free/Premium    |
| **Allergen Safety**        | Detects 8 FDA allergens; premium includes custom sensitivities with severity levels.        | Free/Premium    |
| **Recipe Generator**       | Up to 5 recipes/day (free) or unlimited with advanced filters (premium).                    | Free/Premium    |
| **Wellness Tracking**      | Daily progress score with badges (free); trends and biometric integration (premium).        | Free/Premium    |

---

## 📚 Documentation

- **Product Requirements Document (PRD):** Comprehensive guide to features, requirements, and roadmap.
- **API Specification:** Detailed endpoints for backend integration.
- **Architecture Diagram:** Visual overview of the system design.

---

---

## 🛡️ Project Badges

### 📦 General Project Info
![License](https://img.shields.io/github/license/yenugah80/MyFoodMatrix?style=flat-square)
![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android%20%7C%20Web-blue?style=flat-square)
![Status](https://img.shields.io/badge/MVP%20Launch-August%2020%2C%202025-success?style=flat-square)

---

### ⚙️ Tech Stack
![React Native](https://img.shields.io/badge/Framework-React%20Native-blue?style=flat-square)
![Backend](https://img.shields.io/badge/Backend-Node.js-green?style=flat-square)
![Database](https://img.shields.io/badge/Database-Supabase-lightgrey?style=flat-square)
![Frontend](https://img.shields.io/badge/UI-TailwindCSS-38bdf8?style=flat-square&logo=tailwind-css)

---

### 🤖 AI & Machine Learning
![AI Enabled](https://img.shields.io/badge/AI-OCR%20%7C%20NLP%20%7C%20ML-purple?style=flat-square)
![OCR](https://img.shields.io/badge/OCR-Tesseract.js-orange?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-DistilBERT-yellow?style=flat-square)
![Recipes](https://img.shields.io/badge/Recipes-T5%20%7C%20GPT4o--mini-red?style=flat-square)

---

### 🌐 API & Infrastructure
![API](https://img.shields.io/badge/API-Open%20Food%20Facts%20%7C%20USDA-blueviolet?style=flat-square)
![Deployment](https://img.shields.io/badge/Deploy-Vercel-black?style=flat-square&logo=vercel)
![Monitoring](https://img.shields.io/badge/Monitoring-Prometheus-orange?style=flat-square)

---

### 📊 GitHub Activity
![Issues](https://img.shields.io/github/issues/yenugah80/MyFoodMatrix?style=flat-square)
![Pull Requests](https://img.shields.io/github/issues-pr/yenugah80/MyFoodMatrix?style=flat-square)
![Stars](https://img.shields.io/github/stars/yenugah80/MyFoodMatrix?style=flat-square)

---

### ✅ CI/CD & Quality (Optional – Enable when ready)
![Build](https://img.shields.io/github/actions/workflow/status/yenugah80/MyFoodMatrix/ci.yml?branch=main&style=flat-square)
![Coverage](https://img.shields.io/codecov/c/github/yenugah80/MyFoodMatrix?style=flat-square)

---


## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed and set up before running the project:

- [Node.js (v18+)](https://nodejs.org/en/download/)
- [React Native CLI](https://reactnative.dev/docs/environment-setup)
- [Supabase Account](https://supabase.com/)
- API Keys for:
  - [Open Food Facts](https://world.openfoodfacts.org/data)
  - [USDA FoodData Central](https://fdc.nal.usda.gov/api-key-signup.html)

---

### Installation

#### Clone the repository

```bash
git clone https://github.com/yenugah80/MyFoodMatrix.git
cd MyFoodMatrix
Install Dependencies
Frontend:

bash
Copy
Edit
cd src/frontend
npm install
Backend:

bash
Copy
Edit
cd src/backend
npm install
Configure Environment Variables
Copy .env.example to .env in both src/frontend and src/backend.

Add your Supabase credentials and API keys as per the example file.

Start the Development Servers
Frontend:

bash
Copy
Edit
npm start
Backend:

bash
Copy
Edit
npm run dev
Additional Setup
For more detailed setup and usage instructions, refer to:

src/frontend/README.md

src/backend/README.md

📂 Project Structure
bash
Copy
Edit
MyFoodMatrix/
├── docs/                    # Project documentation
│   ├── MyFoodMatrix_PRD.md  # Product Requirements Document
│   ├── assets/              # Diagrams and images (e.g., architecture.png)
│   ├── api/                 # API specifications (e.g., api_spec.yaml)
├── src/                     # Source code
│   ├── frontend/            # React Native application
│   ├── backend/             # Node.js/Express server
├── .github/                 # GitHub Actions workflows
├── README.md                # Project overview (this file)
├── CONTRIBUTING.md          # Contribution guidelines
├── LICENSE                  # MIT License
├── .gitignore               # Ignored files
🤝 Contributing
We warmly welcome contributions to enhance MyFoodMatrix! Please review our CONTRIBUTING.md for guidelines on:

Submitting PRD updates or feature proposals.

Writing code, unit tests, and documentation.

Reporting issues or suggesting improvements via GitHub Issues.

Contribution Process
Fork the repository and create a new branch:

bash
Copy
Edit
git checkout -b feature-branch
Commit your changes:

bash
Copy
Edit
git commit -m "Add new feature"
Push to the branch:

bash
Copy
Edit
git push origin feature-branch
Open a Pull Request for review.

📜 License
This project is licensed under the MIT License, promoting open-source collaboration and use.

📧 Contact
For questions or support, please contact the product manager at your-email@example.com or open an issue on GitHub.

❤️ Acknowledgements
Built with passion and dedication by the MyFoodMatrix team. Thank you to our contributors and the open-source community!

Last Updated: Wednesday, June 18, 2025



