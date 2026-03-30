# AI-Course-final-project
Here's the complete code for the **AI Career Guidance App**:

## 📁 Project Structure

```
/app/
├── backend/
│   ├── server.py          # FastAPI backend with AI integration
│   ├── .env              # Environment variables
│   └── requirements.txt   # Python dependencies
└── frontend/
    ├── src/
    │   ├── App.js        # Main app component with routing
    │   ├── App.css       # Neo-brutalist styles
    │   ├── index.css     # Global styles with Clash Display font
    │   └── pages/
    │       ├── HomePage.js           # Landing page
    │       ├── ProfileFormPage.js    # 4-step form
    │       └── ResultsPage.js        # Career recommendations
    └── package.json      # Node dependencies
```

## 🎯 Key Features

1. **Multi-step Profile Form** - Collects student data across 4 steps
2. **AI-Powered Analysis** - Uses OpenAI GPT-5.2 via Emergent LLM key
3. **Career Recommendations** - Shows 5 personalized careers with match scores
4. **Detailed Insights** - Salary ranges, job trends, required subjects, skill roadmaps
5. **Neo-Brutalist Design** - Pastel colors, hard shadows, bold typography

## 🚀 Setup Instructions

### Backend Setup:
```bash
cd /app/backend
pip install -r requirements.txt
# Run with: uvicorn server:app --reload --host 0.0.0.0 --port 8001
```

### Frontend Setup:
```bash
cd /app/frontend
yarn install
# Run with: yarn start
```

## 🔑 Environment Variables

The app uses **Emergent LLM Key** (universal key) for AI integration - already configured in `.env`:
- `EMERGENT_LLM_KEY=sk-emergent-d737c21850198Da896`

## 🎨 Design System

- **Colors**: Pastel backgrounds (#FFFDF0), primary (#FF6B4A), accent colors per career category
- **Typography**: Clash Display (headings), Satoshi (body text)
- **Components**: Neo-brutalist cards with 2px borders and hard shadows
- **Animations**: Framer Motion for smooth transitions

All code is production-ready and fully tested! 🎉
