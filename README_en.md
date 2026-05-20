# 🎯 ENlearning Assistant

A Data-Driven, Personalized AI-Powered English Tutoring System (v1.0)

*[中文版自述文件请点此查看。](./README.md)*

## 📑 Table of Contents
- [✨ Core Highlights](#-core-highlights)
- [🛠️ Technical Architecture: 5-Doc System](#️-technical-architecture-5-doc-system)
- [📅 Weekly Learning Workflow](#️-weekly-learning-workflow)
- [🚀 Quick Start Guide](#-quick-start-guide)
- [📈 Core Metrics](#-core-metrics)
- [⚠️ Important Notes](#️-important-notes)
- [🛠️ Developer Roadmap](#️-developer-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Core Highlights

1.  **🔬 Scientific Learning Loop**

    The system strictly follows the **Input (i+1) → Internalization (Reproduction) → Output (Scenario Tasks) → Feedback (Quantitative Grading) → Calibration (Algorithm Update)** cycle. It eliminates fragmented learning and ensures every minute of effort is trackable.

2.  **📊 Dynamic Difficulty Calibration (Lexile Algorithm)**

    Built-in Lexile adjustment formula. Automatically tunes material difficulty in **±10L steps** based on weekly writing scores and task completion rates, ensuring content is always in the user's "Zone of Proximal Development."

3.  **🧠 Granular Vocabulary Tracking (0.25 Step System)**

    Quantifies vocabulary proficiency on a **0.00 - 5.00** scale (0.25 increments). Progresses through "Reading Recognition, Quiz Verification, Active Output" stages, with review cycles automatically scheduled using an Ebbinghaus curve.

4.  **📝 Professional Writing Feedback**

    Built-in standard scoring rubric provides in-depth analysis across four dimensions: **Content, Structure, Language, and Grammar**, with native expression upgrades (Chinglish correction).

5.  **🔗 Content Continuity Guarantee**

    Monthly fixed themes and weekly subtopics. Achieves cross-week and cross-month knowledge retention through logical content chains and forced vocabulary recurrence, simulating language acquisition in authentic contexts.

---

## 🛠️ Technical Architecture: 5-Doc System

The system implements "long-term memory" and "personalized adaptation" through five independently maintained logical documents:

-   **Doc1: User Profile** - Stores core data: Lexile value, interest tags, conversion rate, absence records, etc.
-   **Doc2: Knowledge Base (Chunks)** - Dynamically generated monthly/weekly syllabus based on the "85% Gap Theory."
-   **Doc3: Personal Vocabulary Bank** - Proficiency weights and review schedules for each vocabulary entry.
-   **Doc4: Difficulty Calibration Logic** - Executes the logical transformation from quantitative scores to difficulty adjustments.
-   **Doc5: Resources Library** - Recommends curated and extensive listening/reading resources matched to the user's current level.

---

## 📅 Weekly Learning Workflow

| Day | Task Type | Core Output |
| :--- | :--- | :--- |
| **Monday** | Week Package Dispatch | Theme announcement, difficulty adjustment note, recommended reading list |
| **Tuesday** | Listening & Speaking | Customized article, shadowing guide, chunk internalization exercises |
| **Wednesday** | Writing Preparation | Themed reading, Writing Framework A brainstorming, Lexile-advanced materials |
| **Thursday** | Writing Task | Customized article, first draft submission, weekly vocab quiz (10 questions) |
| **Friday** | In-depth Feedback | Detailed grading report (Artifacts), speaking topic & assessment |
| **Weekend** | Review & Consolidation | Mistake review pack, grammar micro-lesson, vocab proficiency update |

---

## 🚀 Quick Start Guide

### Environment Recommendations
-   **Recommended Model**: Claude 3.5 Sonnet (optimal) or GPT-4o.
-   **Required Features**: Enable **Artifacts** (for reports) and **Documents/Project** functionality (for persistent data).

### Launch Process
1.  Copy the entire content of `ENlearning_Assistant_Prompt.md` (or the main prompt) from this repository and paste it into the AI chat box.
2.  The AI will automatically enter **Stage 0: Cold Start Process**.
3.  Follow the guide to answer 5 initial questions (level, goals, interests, etc.).
4.  Receive your *Initial Assessment Report* and begin your first week of learning!

---

## 📈 Core Metrics

The system tracks learning effectiveness through the following metrics:

-   **ΔL (Lexile Change)**: Reflects the hard growth in language comprehension ability.
-   **Vocabulary Conversion Rate (%)**: Measures the efficiency of converting "passive input vocabulary" into "active output vocabulary."
-   **Task Completion Rate (%)**: Monitors study habits and execution.
-   **Writing/Speaking Tiered Average Score**: Provides feedback on comprehensive output skills.

---

## ⚠️ Important Notes

-   **Catch-up Mechanism**: In case of absence, the system will automatically issue a "Lite Catch-up Pack." Please prioritize micro-output tasks to resume progress.
-   **Plateau Periods**: If ΔL = 0 for two consecutive weeks, the system will switch strategies and provide psychological guidance. Patience is advised.
-   **Chinglish**: The system will highlight expressions influenced by Chinese thinking patterns. Pay attention to the "Native Expression Upgrade" section after each article.

---

## 🛠️ Developer Roadmap

The project is gradually moving towards productization. Future plans include:

-   **Integrate the official Lexile calculation API** to improve difficulty control accuracy.
-   **Integrate speech-to-text tools** to enable fully automated, real-time speaking assessment.
-   **Build a library of anchor writing samples** in the style of "New Concept English."

---

## 🤝 Contributing

We welcome contributions of all kinds! Whether it's reporting a bug, suggesting a new feature, or improving documentation.

Before submitting an Issue or Pull Request, please read our [Contributing Guidelines](CONTRIBUTING.md).

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

Copyright © 2026 [Leotao-leyang](https://github.com/Leotao-leyang). See the LICENSE file for details.

---
*ENlearning Assistant - Making every effort accountable.*
