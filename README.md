# Scam Message Investigator

## Project Overview

Scam Message Investigator is an AI-powered web application developed using Python and Streamlit. It analyzes suspicious SMS messages, emails, job offers, and online messages to identify potential scam indicators.

The application uses the Gemma 3 1B language model through Ollama to examine message content and generate an investigation report with risk levels, warning signs, and recommended safety actions.

## Objectives

- Identify potential online scam messages.
- Analyze suspicious message content using AI.
- Detect warning signs and possible phishing attempts.
- Extract URLs from suspicious messages.
- Provide safety recommendations to users.
- Generate structured investigation reports.

## Features

- AI-based scam message analysis.
- Message category identification.
- Risk classification into Low, Medium, and High Concern.
- Suspicious URL extraction.
- Warning sign identification.
- Recommended safety actions.
- Investigation limitations and explanations.
- Local AI processing using Ollama.

## Technologies Used

- Python
- Streamlit
- Ollama
- Gemma 3 1B
- Requests
- JSON

## Sample Input

```text
URGENT: Your SBI bank account will be blocked
within 24 hours due to incomplete KYC verification.
To avoid account suspension, immediately update
your KYC details. Send your bank account number,
ATM PIN and OTP to complete the verification process.
Failure to respond will result in permanent account closure.
```

## Expected Output

- Risk Level: High Concern
- Message Type: Banking / KYC Verification Scam
- Summary of the suspicious message.
- Extracted links.
- Identified warning signs.
- Recommended safety actions.
- Investigation limitations.

## Applications

- Identifying suspicious banking messages.
- Analyzing fraudulent job offers.
- Recognizing phishing attempts.
- Examining suspicious parcel delivery messages.
- Improving online safety awareness.

## Limitations

- The application analyzes only the text provided by the user.
- It does not independently verify the sender's identity.
- It does not verify whether a website is malicious.
- AI-generated results may not always be accurate.
- Internet-based link verification is not included.

## Future Enhancements

- Cloud deployment.
- Improved scam classification.
- Support for multiple languages.
- Advanced URL reputation checking.
- Email and SMS integration.
