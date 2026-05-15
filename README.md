# ExpressWay Logistics - Sentiment Analysis

Sentiment analysis on courier service reviews using prompt engineering (Zero-shot & Few-shot) with Groq LLaMA API.

## Project Overview
Classifies customer reviews for ExpressWay Logistics as Positive or Negative using:
- Zero-shot prompting
- Few-shot prompting
- Micro-F1 score evaluation

## Setup
1. Get a free API key from https://console.groq.com
2. Create a `config.json` file in the project folder:
```json
{
    "GROQ_API_KEY": "YOUR_GROQ_API_KEY_HERE",
    "GROQ_MODEL": "llama-3.1-8b-instant"
}
```
3. Install dependencies:
pip install groq tiktoken scikit-learn pandas numpy tqdm tabulate
4. Run all cells top to bottom

## Dataset
`courier-service_reviews.csv` — customer reviews with sentiment labels (Positive/Negative)

## Results
- Zero-shot and Few-shot prompts evaluated over 5 runs
- Metrics: Mean and Standard Deviation of Micro-F1 score
