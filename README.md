# LLMisses — Multi-Agent Mock Interview Agent

An AI mock interviewer: your interview rehearsal, anytime, anywhere.

**LLMisses** is a web application that helps job seekers sharpen their interview skills through realistic, tailored mock interview sessions. A multi-agent LLM framework simulates the interview step by step — asking role-specific questions, listening to your spoken answers, and returning real-time, in-depth, actionable feedback.

▶️ **[Video demo](https://youtu.be/dRxGk8MP5Fc)** · 📝 **[Medium writeup](https://medium.com/@wendyXdata/ai-enabled-mock-interviewer-7f336cb8124a)** · 📖 **[User guide](https://docs.google.com/presentation/d/1bjm0Sk-CkGZmKPyN5jOXONspp56Mfup3zcvKQHhWV8M/edit?pli=1#slide=id.gc6f80d1ff_0_66)**

---

## Features

- **Multi-agent framework** — separate agents drive the interview flow step by step, keeping the session well-guided and realistic while maintaining high-quality interactions.
- **Industry-specific scenarios** — customize interviews for tech, consulting, healthcare, and more.
- **Role-specific questions** — questions tailored to the job description and level of experience you upload.
- **Real-time feedback** — AI-generated feedback on each answer, including strengths and areas to improve.
- **Voice-first interface** — audio conversation by default, with optional text chat.
- **Analytics dashboard** — track performance over time with detailed metrics and actionable suggestions.

---

## Installation

### Prerequisites
- Python 3.8+
- An OpenAI API key
- Flask

### Clone the repository
```bash
git clone https://github.com/Yanan-Gong/LLMisses-mock-interview-agent
cd LLMisses-mock-interview-agent
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Launch the app
```bash
flask run
```

## Usage

1. Open your browser and navigate to `http://127.0.0.1:5000`.
2. Upload your resume, target industry, and job description.
3. Start the mock interview and talk with the AI interviewer.
4. Review feedback and performance analytics after the session.

---

## Technology stack

- **Backend**: Python (Flask)
- **Frontend**: HTML, JavaScript, CSS
- **LLM integration**: OpenAI API
- **Deployment**: Docker, AWS/GCP/Azure (in progress)

---

## Contributing

Contributions are welcome:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push them to your fork:
   ```bash
   git push origin feature-name
   ```
4. Open a pull request.

---

## Contact

For questions or feedback, reach out to **LLMisseshackathon@gmail.com** or open an issue in this repository.
