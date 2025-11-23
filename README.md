# finance-tracker
Personal finance tracking app with budgeting and multi-currency support
# Finance Tracker

A full-stack personal finance tracking application with user authentication, budgeting, multi-currency support, and WhatsApp integration.

## Features

- 💰 Income & Expense Tracking
- 🔐 Secure User Authentication (JWT + Bcrypt)
- 📊 Monthly Budgeting with Alerts
- 💱 Multi-Currency Support (9 currencies)
- 📱 WhatsApp Sharing
- 📥 CSV Export
- 📈 Visual Dashboard with Charts
- 🌐 Mobile Responsive

## Tech Stack

**Frontend:**
- React 18 + Vite
- React Router DOM
- Recharts
- Vanilla CSS

**Backend:**
- FastAPI
- SQLAlchemy
- PostgreSQL
- JWT Authentication

## Local Development

### Backend
```bash
cd server
pip install -r requirements.txt
python -m uvicorn main:app --reload
```

### Frontend
```bash
cd client
npm install
npm run dev
```

## Deployment

See `deployment_guide.md` for complete deployment instructions.

## License

MIT
