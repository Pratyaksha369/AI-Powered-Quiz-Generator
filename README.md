# AI-Powered-Quiz-Generator

## Overview
Preparing for competitive exams like UPSC (Union Public Service Commission) and PCS (Provincial Civil Service) presents unique challenges:

- Limited availability of high-quality practice questions.
- Lack of instant feedback on performance.
- Difficulty in tailoring question difficulty to individual needs.
- Time-intensive creation and evaluation of practice tests.
- Insufficient coverage of diverse topics across subjects.

This project aims to solve these issues by providing an AI-powered automated quiz generation system tailored for UPSC and PCS exam preparation.

---

## Industry Applications
This project is valuable across multiple domains:

### Education & Test Prep
- Coaching institutes
- Online learning platforms
- Self-study programs
- Educational assessment tools

### Competitive Exam Training
- UPSC preparation centers
- State PCS coaching programs
- Government job exam preparation
- Assessment centers

### Corporate Training
- Employee assessment tools
- Professional development programs
- Knowledge testing solutions
- Skill evaluation systems

---

## Tools & Technologies
Core Technologies
- Python 3.8+
- Streamlit: Interactive web interface
- Groq LLM API: Advanced AI for question generation
- Pandas: Data manipulation and handling

## Libraries & Frameworks
- langchain-groq
- pydantic
- python-dotenv
- streamlit
- pandas
  

## Setup Instructions

1. Clone the Repository
```bash
git clone <repository-url>
cd upsc-pcs-quiz-generator
```

2. Create Virtual Environment
```bash
conda create -p env python=3.10 -y
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Environment Configuration Create a .env file in the root directory:
```bash
GROQ_API_KEY=your_groq_api_key_here
```

5. Run the Application
```bash
streamlit run app.py
```
---


## Key Features
### Question Generation
- Multiple-choice and fill-in-the-blank questions.
- Adjustable difficulty levels.
- Topic-specific question sets.

### Quiz Management
- Interactive quiz interface.
- Real-time scoring and feedback.
- Progress tracking.

## Result Analysis
- Score calculation.
- Detailed performance metrics.
- Exportable results.
- Historical data tracking for improvement.
