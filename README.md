# 🛡️ ScamShield AI

> **An AI-powered digital fraud-safety chatbot built with Google Dialogflow ES**

ScamShield AI is a digital fraud-safety chatbot developed with **Google Dialogflow ES** for the *Artificial Intelligence: Real-World Applications and Implications* summative assessment.

It is designed to help **digital payment users, job seekers, students, older adults, and online shoppers** recognize fraudulent situations, understand common scam types, decide what to do next, and improve their awareness through simple guidance and quizzes.

---

## 📌 Project Overview

Online scams can be difficult to recognize, especially when messages create urgency, impersonate trusted organizations, or request sensitive information.

**ScamShield AI** provides users with structured, easy-to-understand guidance for identifying suspicious situations and responding safely.

The chatbot focuses on:

* 🚨 Recognizing common scam warning signs
* 🛡️ Taking appropriate immediate safety actions
* 💡 Understanding different types of digital fraud
* 🧠 Building long-term scam awareness
* 📝 Testing knowledge through awareness quizzes

---

# ✨ Main Features

### 🚨 Scam Warnings & Prevention

Provides clear warnings about suspicious situations along with practical preventive safety tips.

### 🆘 Emergency Safety Guidance

Provides guidance for situations involving:

* Stolen money
* Shared OTPs
* Hacked accounts
* Threats
* Remote-access incidents

### 🔎 Suspicious-Message Assessment

Uses **slot filling** to guide users through a suspicious-message assessment and collect relevant details before providing guidance.

### 🧩 Context-Aware Conversations

Uses contexts and follow-up questions to maintain conversational relevance and route users toward appropriate guidance.

### 💬 Natural User Interaction

Supports:

* Quick replies
* Suggestion chips
* Awareness quizzes
* Informal language
* Common spelling mistakes
* Fallback handling

---

# 🧠 Intents & Entities

ScamShield AI contains:

| Component                    |  Quantity |
| ---------------------------- | --------: |
| 🎯 Focused intents           |    **42** |
| 🛡️ Fraud & safety topics    |   **113** |
| 🧩 Custom entities           |   **100** |
| 📝 Training phrases          | **1,891** |
| 🧪 Independent test messages |   **339** |

### 🎯 Intent Coverage

The **42 focused intents** cover **113 fraud and safety topics**, including:

* UPI, OTP, QR-code, refund, and banking scams
* Phishing emails, smishing messages, and fraudulent calls
* Fake jobs, investments, loans, prizes, shopping, and romance scams
* Account takeover, identity theft, malware, and remote-access risks
* Incident reporting
* Evidence preservation
* Prevention tips
* Awareness quizzes

### 🧩 Custom Entities

The chatbot uses **100 custom entities** to recognise important details such as:

* Scam type
* Sender claim
* Message channel
* Requested action
* Payment method
* Urgency
* Incident stage
* Risk indicator
* Device type
* Account type

Required parameters allow ScamShield AI to ask useful follow-up questions before providing guidance.

---

# 🧪 Testing & Optimization

Every intent was tested using **varied natural queries and realistic end-to-end scenarios**.

The final design includes:

* **1,891 training phrases**
* **Zero exact phrase overlaps between intents**
* **339 independently generated test messages**

Responses were refined to improve:

* 🚨 Emergency routing
* 🧠 Clarity
* 🎯 Relevance
* 🛡️ User safety

This testing and optimization process helped ensure that the chatbot could handle different ways users might naturally describe suspicious situations.

---

# ⚙️ Integration & Deployment

ScamShield AI runs entirely within **Google Dialogflow ES** and uses its built-in capabilities, including:

* Intent matching
* Entities
* Contexts
* Slot filling
* Rich responses
* Fallback handling

### 🔌 External Dependencies

The chatbot does **not** require:

* Gemini
* A webhook
* An external API
* A database
* Secret keys

The chatbot can be published through a **Dialogflow web integration** and shared using its live demonstration URL.

---

# 🌐 Live Chatbot

### Try ScamShield AI

**[ADD LIVE CHATBOT LINK]**

> Replace the placeholder above with the live Dialogflow web integration URL when available.

---

# ⚖️ Ethical & Safety Considerations

ScamShield AI is designed as an **educational fraud-safety tool**.

The chatbot:

* Does **not** claim that a person, message, or transaction is genuine.
* Does **not** request OTPs, PINs, passwords, full card details, or identity numbers.
* Provides educational safety guidance.
* Does **not** replace assistance from a bank, platform, police service, or relevant authority.

Its purpose is to help users **recognize potential risks and make safer decisions**, rather than to independently verify whether a transaction or individual is legitimate.

## 🛡️ ScamShield AI

**Recognize the warning signs.
Understand the risk.
Take safer action.**
