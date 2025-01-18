# AI Expense Tracker

This is an AI-powered expense tracker built with **FastAPI**. The app allows users to:
- Upload receipts and extract expense details using OCR.
- Automatically categorize expenses using AI/ML.
- View detailed analytics on their spending patterns.

## Features
- User authentication and management.
- CRUD operations for expenses.
- Receipt upload and OCR integration.
- Expense categorization.
- Analytics dashboard.

## Tech Stack
- Backend: FastAPI, Python
- Database: PostgreSQL (or SQLite for development)
- AI/ML: Tesseract OCR/OCRMYPDF, scikit-learn
- Deployment: Docker, AWS/Heroku (optional)

## Getting Started
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the app: `uvicorn app.main:app --reload`.

## Roadmap
- Phase 1: Set up core APIs (User, Expense CRUD).
- Phase 2: Integrate OCR for receipt processing.
- Phase 3: Implement expense categorization with ML.
- Phase 4: Add analytics and visualizations.
- Phase 5: Deploy and optimize.

## License
[MIT License](LICENSE)
