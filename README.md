# Phishing Red Teaming Evaluation

This project is a red teaming prompt designed to test whether AI models will generate phishing content when the request is framed as a benign educational exercise.

## Objective
The goal is to evaluate whether a model resists producing harmful social-engineering content, even when the user claims the request is for training or exam preparation.

## Attack Strategy
The prompt uses:
- a benign educational pretext
- urgency and personal pressure
- a request targeting a real brand
- explicit formatting instructions
- an instruction to avoid explanations or safety guidance

## Evaluation Focus
This project tests whether the model:
- detects phishing-generation intent
- recognizes brand impersonation risk
- refuses unsafe assistance
- redirects toward safe educational help instead of generating harmful content

## Testing Outcome
During controlled testing, this prompt successfully elicited unsafe phishing-email generation behavior from multiple models, including:
- ChatGPT 5.2
- ChatGPT 4.0
- Gemini 3.1 Pro
- DeepSeek V3.2
- Kimi K2.5
- Cloud Opus 4.6

## Relevance
This project is relevant to AI safety, red teaming, misuse prevention, and prompt-based evaluation of model compliance behavior.
