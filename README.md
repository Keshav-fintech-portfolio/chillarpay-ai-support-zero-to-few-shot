# AI for Customer Support in a FinTech App
### ChillarPay Case Study – Lab Assignment 02

![AI](https://img.shields.io/badge/AI-Customer%20Support-blue)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-Zero--Shot%20%7C%20Few--Shot-green)
![Domain](https://img.shields.io/badge/Domain-FinTech-orange)

## 📌 Project Overview

This project explores how Artificial Intelligence (AI) can improve customer support operations in a FinTech application called **ChillarPay**.

The project focuses on using AI to:
- Categorize customer support messages.
- Identify the priority of customer complaints.
- Generate polite and helpful customer replies.
- Compare Zero-Shot Prompting and Few-Shot Prompting techniques.

The objective is to understand how prompt engineering can make AI-based customer support more accurate, efficient, and reliable.

## 🎯 Objectives

1. Understand the role of AI in FinTech customer support.
2. Develop a Zero-Shot prompt for customer message classification.
3. Develop a Few-Shot prompt using examples.
4. Classify messages into different support categories.
5. Assign High, Medium, and Low priority levels.
6. Compare the performance of both prompting techniques.
7. Identify the importance of human supervision in AI-generated responses.

## 🏦 Case Study: ChillarPay

ChillarPay is a fictional UPI payment application based in Jaipur.

- **Users:** Approximately 8 lakh.
- **Daily Support Messages:** Around 2,000.
- **Support Team:** 6 members.
- **Languages:** English and Hinglish.

The main challenge is identifying urgent fraud cases among thousands of regular customer queries.

## 📂 Support Categories

Customer messages are classified into four categories:

| Category | Description |
|---|---|
| Failed Payment | Payment failed or money deducted |
| Refund | Refund-related complaints |
| Fraud Alert | Suspicious activities and unauthorized transactions |
| Account & KYC | Login, account blocking and KYC issues |

## 🚦 Priority Classification

| Priority | Conditions |
|---|---|
| High | Money lost without consent or account blocked |
| Medium | Money stuck, delayed payments or pending refunds |
| Low | General information requests or profile updates |

## 🤖 Prompt Engineering Techniques

### 1. Zero-Shot Prompting

Zero-Shot Prompting provides AI with instructions and rules without giving any solved examples.

It is used to:
- Identify message categories.
- Assign priority levels.
- Generate customer support replies.

### 2. Few-Shot Prompting

Few-Shot Prompting provides AI with instructions along with six solved examples.

These examples help AI understand:
- Scam messages without financial loss.
- Failed payments.
- Angry customer complaints.
- Unauthorized transactions.
- Blocked accounts.
- General information requests.

## 📊 Results and Performance Comparison

The assignment compares both prompting techniques using 12 synthetic customer messages.

| Performance Metric | Zero-Shot | Few-Shot |
|---|---:|---:|
| Category Accuracy | 83% | 100% |
| Priority Accuracy | 67% | 92% |
| Reply Rule Compliance | 75% | 100% |
| All Three Correct | 42% | 92% |
| High-Priority Cases Detected | 2/3 | 3/3 |
| False High Alerts | 2 | 0 |

**Key Finding:** Few-Shot Prompting performed better than Zero-Shot Prompting across all major evaluation metrics.

*Note: These are simulated results prepared for the assignment, not verified results from a live AI system.*

## 💡 Key Learnings

- Simple prompts work well for clear and standard customer queries.
- Examples improve AI performance in complicated situations.
- Priority classification is important in financial applications.
- AI should follow business rules rather than customer emotions.
- Human approval is necessary for high-priority and fraud-related responses.
- Customer information such as UPI PINs and OTPs must remain protected.

## 🚀 Recommendations

1. Use Few-Shot Prompting for better classification and response generation.
2. Maintain human supervision for urgent and fraud-related cases.
3. Improve business rules for unclear KYC-related situations.
4. Test the system using 100–200 anonymized real customer messages.
5. Protect sensitive customer information.
6. Regularly update examples to handle new fraud patterns.

## 🛠️ Tools and Concepts Used

- Artificial Intelligence (AI)
- Machine Learning (ML) Concepts
- Prompt Engineering
- Zero-Shot Prompting
- Few-Shot Prompting
- Customer Message Classification
- FinTech and UPI Payments

## 📁 Project Structure

```text
AI-Customer-Support-ChillarPay/
│
├── README.md
├── Lab 02.docx
└── Project Documentation
```

## 🎓 Conclusion

This project demonstrates that AI can help FinTech applications improve customer support by automating message classification, priority identification, and reply drafting.

Few-Shot Prompting provides better results than Zero-Shot Prompting, especially for complex customer queries.

The recommended approach is to combine Few-Shot Prompting, clear business rules, data protection, and human supervision.

---

⭐ **Thank you for visiting this project!**
