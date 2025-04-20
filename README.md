# LLM-Audit-Customer-Service-Calls

Thanks for the notebook and context! Based on your project description and the content from your Jupyter notebook, here’s a clean and informative `README.md` file you can use for your GitHub repository:

---

# 🎧 AI-Powered Customer Service Call Auditor

This project implements an AI-driven solution for auditing customer service calls. It combines cutting-edge speech recognition with advanced language model analysis to evaluate customer service quality efficiently and effectively.

## 🚀 Project Overview

The system is designed to transcribe call audio, evaluate transcription accuracy, assess service quality, and generate a comprehensive report. It uses:

- **OpenAI Whisper** for high-quality speech-to-text transcription
- **`jiwer`** for calculating Word Error Rate (WER) to measure transcription accuracy
- **Gemini (Google's LLM)** for natural language evaluation of customer service quality
- **Python & Jupyter Notebook** for implementation and reporting

## 🧠 Key Components

1. **Audio Transcription**  
   Uses OpenAI Whisper to convert spoken language into written text.

2. **WER Calculation**  
   Implements the `jiwer` library to compute the Word Error Rate between ground truth and predicted transcriptions.

3. **Quality Assessment with Gemini**  
   Prompts Gemini to analyze the transcription and rate customer service quality based on key criteria like:
   - Tone and Empathy
   - Problem Resolution
   - Professionalism
   - Overall Experience

4. **Report Generation**  
   Automatically generates a structured report summarizing:
   - Transcription
   - WER Score
   - Qualitative feedback from Gemini
   - Final Quality Rating

## 📊 Sample Output

The output of the system includes:

- Transcribed call text
- WER Score (accuracy)
- Gemini evaluation:
  ```
  Tone and Empathy: 4/5
  Problem Resolution: 5/5
  Professionalism: 5/5
  Overall Experience: 4.5/5
  Comments: The agent was polite and resolved the issue efficiently...
  ```

## ✅ Use Cases

- Customer service QA audits
- Call center training feedback
- Automated quality scoring
- Voice-to-text AI integrations

## 📌 Future Improvements

- Add support for batch processing of multiple calls
- Visual dashboards for trends and insights
- Sentiment analysis integration
- Multi-language support

## 📃 License

This project is licensed under the MIT License.

---