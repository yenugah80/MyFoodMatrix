MyFoodMatrix

MyFoodMatrix is a cross-platform mobile application (iOS, Android, web) that empowers health-conscious users to log meals, track nutritional quality, ensure diet and allergen compliance, generate personalized recipes, and monitor wellness goals with AI-driven insights. Available in free and premium tiers, it simplifies nutrition for fitness enthusiasts, home cooks, and those with dietary restrictions.
✨ Features

📸 Photo/Text Meal Logging: Upload food photos or text to log meals, powered by OCR (Tesseract.js) and NLP (DistilBERT).
🍎 Smart Nutrition Score: 0–100 score (A–D) for macronutrient balance and micronutrient density.
🥗 Diet Compatibility: Supports keto, vegan, gluten-free diets with compliance flags.
🚨 Allergen Safety: Detects 8 FDA allergens for safe meal planning.
📝 Recipe Generator: Personalized recipes with ingredients, instructions, and nutritional breakdowns.
📊 Wellness Tracking: Daily progress scores with gamified badges.

📑 Documentation

Product Requirements Document (PRD)
API Specification
Architecture Diagram

🚀 Getting Started
Prerequisites

Node.js v18+
React Native CLI
Supabase account
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
Add Supabase credentials and API keys.


Start the development server:
Frontend: npm start
Backend: npm run dev



See Frontend README and Backend README for detailed setup.
📂 Project Structure
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
├── LICENSE                  # MIT License
├── .gitignore               # Ignored files

🤝 Contributing
We welcome contributions! Please read CONTRIBUTING.md for details on:

Submitting PRD updates or feature proposals.
Writing code and tests.
Reporting issues via GitHub Issues.

📜 License
This project is licensed under the MIT License.
📬 Contact
For questions, contact the product manager at [your-email@example.com] or open an issue on GitHub.

Built with ❤️ by the MyFoodMatrix team.
