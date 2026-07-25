# 🎓 CertifyAI

### Adaptive Certification Exam Preparation Platform

CertifyAI is a browser-based certification exam preparation platform designed to make practice more adaptive, measurable, and interactive.

Instead of only answering static practice questions, CertifyAI tracks performance, identifies weak domains, creates review opportunities, supports mock examinations, and can optionally use AI to explain questions.

The application runs directly in your browser and can also be downloaded and used locally.

---

## ✨ Features

### ⚡ Adaptive Practice
Practice questions while CertifyAI tracks your performance across exam domains and focuses learning on weaker areas.

### 📝 Mock Exam Mode
Simulate certification exam conditions with:

- Timed examinations
- 65-question mock tests
- Question navigation
- Question flagging
- Confidence tracking
- Final score calculation
- Performance summary
- Domain-level analysis

### 🧠 Spaced Repetition Flashcards
Incorrectly answered concepts can be converted into flashcards for repeated revision.

Cards can be marked:

- **Still Learning**
- **Got It!**

This helps reinforce concepts that need additional practice.

### 🔁 Missed Review
Revisit questions you previously answered incorrectly and practice weak concepts again.

### 📊 Performance Analytics
CertifyAI tracks:

- Overall accuracy
- Questions answered
- Estimated exam readiness
- Current learning level
- Domain performance
- Correct and incorrect answers
- Average time per question
- XP earned

### 🎯 Domain Performance Tracking
Performance can be tracked independently for each certification exam domain.

For example, an AWS Certified Cloud Practitioner pack can track areas such as:

- Cloud Concepts
- Security & Compliance
- Cloud Technology & Services
- Billing, Pricing & Support

### ⭐ XP & Progress System
Users earn XP while practicing and can track their progress over time.

### 🤖 Optional AI Tutor
CertifyAI can connect to supported AI/LLM providers to generate additional explanations for practice questions.

The application is designed so that AI is optional — normal practice functionality works without an AI provider.

Supported/configurable integrations may include:

- Google Gemini
- OpenAI
- Anthropic Claude
- Local Ollama models

Availability depends on the application version and provider configuration.

> API keys are provided by the user. Never publish API keys inside your GitHub repository.

### 📦 JSON Exam Packs
CertifyAI is not limited to a single certification.

Custom exam packs can be imported using JSON.

This makes it possible to build practice packs for certifications such as:

- AWS
- Google Cloud
- Microsoft Azure
- Kubernetes
- SAP
- Other technical certifications

provided the exam pack follows the CertifyAI JSON structure.

### 💾 Local Progress
Learning progress is stored locally in the browser.

Users can also export progress as JSON for backup or transfer.

### 🎨 Customizable Interface
The application includes:

- Dark mode
- Light mode
- Multiple accent colors
- Responsive interface
- Mobile and desktop support

---

# 📸 Application Preview

Screenshots of the application will be added here.

Suggested screenshots:

1. Dashboard
2. Adaptive Practice
3. Mock Exam
4. Spaced Repetition Flashcards
5. Performance Analytics
6. Final Exam Result
7. AI Tutor
8. Settings

---

# 🚀 Online Version

CertifyAI can be hosted as a static web application using GitHub Pages.

Once deployed, users can open the application directly from their browser without installing software.

---

# 💻 Run Locally

CertifyAI can also be downloaded and used locally.

## Option 1 — Download ZIP

1. Open the GitHub repository.
2. Select **Code**.
3. Select **Download ZIP**.
4. Extract the ZIP file.
5. Open the main HTML file in a browser.

For the best compatibility, running the application through a small local web server is recommended.

## Option 2 — Clone with Git

```bash
git clone YOUR_REPOSITORY_URL
cd CertifyAI
