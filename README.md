# Watch Insurance Advisor

A beautiful, AI-powered chatbot that helps users decide whether insuring their watch makes financial sense.

![Watch Insurance Advisor](https://img.shields.io/badge/Powered%20by-GPT--4-brightgreen)
![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Flask](https://img.shields.io/badge/Flask-3.0+-lightgrey)

## Features

- **Conversational AI** — Natural, flowing conversation powered by GPT-4
- **Premium UI** — Elegant gold and navy design matching luxury watch aesthetics
- **Smart Recommendations** — Uses financial logic (inspired by Kelly Criterion) without showing math
- **Mobile Responsive** — Works beautifully on all devices
- **Privacy Focused** — No data stored, conversations reset on refresh

## Quick Start

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/WatchInsurance.git
cd WatchInsurance
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set up environment variables

```bash
cp .env.example .env
# Edit .env and add your OpenAI API key
```

### 4. Run the application

```bash
python app.py
```

### 5. Open your browser

Visit [http://localhost:8080](http://localhost:8080)

## Project Structure

```
WatchInsurance/
├── app.py                      # Flask backend
├── templates/
│   └── index.html              # Chat UI template
├── static/
│   ├── css/
│   │   └── style.css           # Premium styling
│   └── js/
│       └── chat.js             # Chat client logic
├── watch_insurance_prompt.txt  # AI system prompt
├── watch_insurance_agent.py    # Terminal-based agent (alternative)
├── requirements.txt            # Python dependencies
├── .env.example                # Environment template
└── README.md
```

## How It Works

The advisor asks 4-5 quick questions:
1. **Watch Value** — What's the approximate value?
2. **Financial Picture** — Is it a small, moderate, or significant portion of your assets?
3. **Premium** — Do you have a quote, or should we estimate?
4. **Usage** — How do you wear and store it?
5. **Deductible** — Is there a deductible? (if applicable)

Then provides a clear recommendation based on your situation.

## Deployment

The app is ready for deployment on:
- **Heroku**
- **Railway**
- **Render**
- **Vercel** (with serverless adapter)

Set the `OPENAI_API_KEY` environment variable in your deployment platform.

## License

MIT License - feel free to use and modify.

---

*This is for informational purposes only and does not constitute financial advice.*
