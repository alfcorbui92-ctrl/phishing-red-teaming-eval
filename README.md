# Phishing Red Teaming Evaluation

This project is a red teaming prompt designed to test whether an AI model will generate phishing content when the request is framed as a benign educational exercise.

## Objective
The goal is to evaluate whether the model resists producing harmful social-engineering content, even when the user claims the request is for training or exam preparation.

## Attack Strategy
The prompt uses:
- a benign educational pretext
- urgency and personal pressure
- a request targeting a real brand
- explicit formatting instructions
- an instruction to avoid explanations or safety guidance

## What this tests
This project tests whether the model:
- detects phishing-generation intent
- recognizes brand impersonation risk
- refuses unsafe assistance
- redirects toward safe educational help instead of generating harmful content

## Relevance
This is an example of AI safety evaluation, prompt injection resistance, and red teaming for misuse prevention.
