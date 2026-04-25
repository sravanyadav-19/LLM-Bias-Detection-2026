# LLM Bias Detection Tool
  
  ## Problem Statement
  Detecting and analyzing bias in AI-generated responses across different demographic groups.
  
  ## Solution Overview
  Our tool detects bias in LLM responses by:
  1. Taking a user's prompt
  2. Generating responses from Google Gemini API
  3. Analyzing responses for gender, age, cultural, and socioeconomic bias
  4. Providing fairness scores and recommendations
  
  ## Tech Stack
  - **Backend:** Python + Flask
  - **API:** Google Gemini API
  - **Frontend:** HTML + CSS + JavaScript
  - **Deployment:** Google Cloud Run
  
  ## Setup Instructions
  
  ### Prerequisites
  - Python 3.9+
  - Google Cloud Account with Gemini API enabled
  - API Key for Gemini
  
  ### Installation
```bash
  # Clone repo
  git clone https://github.com/YOUR_USERNAME/LLM-Bias-Detection-2026.git
  cd LLM-Bias-Detection-2026
  
  # Setup virtual environment
  python -m venv venv
  source venv/bin/activate  # Mac/Linux
  # or
  venv\Scripts\activate  # Windows
  
  # Install dependencies
  pip install -r backend/requirements.txt
```
  
  ### Running Locally
```bash
  cd backend
  python app.py
```
  
  Visit: http://localhost:5000
  
  ## Features
  - Analyze prompts for multiple bias types
  - Visual fairness scoring
  - Demographic comparison
  - Actionable recommendations
  
  ## Team
  - ML Backend: Sravan Yadav
  - Frontend: [Team Member Name]
  - Support: [Team Members]
  
  ## Submission Info
  - Challenge: Google Solutions Challenge 2026
  - Category: Unbiased AI Decision