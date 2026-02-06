# 👟 Sneaker Hunter AI - Market Intelligence Platform (Local AI)

![Project Version](https://img.shields.io/badge/version-3.0-blue)
![Python Version](https://img.shields.io/badge/python-3.8%2B-green)
![Intelligence](https://img.shields.io/badge/AI-ResNet50-orange)

Sneaker Hunter AI is a comprehensive ecosystem designed to bridge the gap between visual identification and market decision-making. Built for the Indian sneaker community, it transforms a simple photo into a full market intelligence report.

## ✨ Key Features

*   **🔍 Precision ID**: Powered by a fine-tuned ResNet50 neural network for accurate silhouette identification.
*   **📈 Price Intelligence**: 6-month price trend visualizations for informed buying.
*   **📖 Sneaker History**: In-depth history, stories, and "quick facts" about every model.
*   **🇮🇳 Indian Market Focus**: Direct links to trusted resellers like VegNonVeg, Superkicks, and CDC.
*   **💎 Premium UI**: Modern dark theme with glassmorphism, fluid animations, and responsive dashboard.
*   **🛡️ Privacy First**: Strict input validation and automatic image cleanup after processing.

## 🚀 Technical Architecture

1.  **AI Engine**: ResNet50 Deep Learning model (Fine-tuned via FastAI).
2.  **Backend**: Flask (Python) with integrated sneaker database lookup.
3.  **Frontend**: Vanilla HTML5/CSS3 with Chart.js for data visualization.
4.  **Security**: `secure_filename()` sanitization and local image wiping for privacy.

## 🛠️ Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ftadieee/Sneaker-Image-Classifier.git
    cd Sneaker-Image-Classifier
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Train the Model (Recommended for fresh setups):**
    ```bash
    python train_model.py
    ```

4.  **Run the app:**
    ```bash
    python app.py
    ```

## 📂 Project Structure

```text
├── app.py                # Main Flask Backend
├── train_model.py        # Model Training Script
├── sneaker_database.json # Local data for reseller mapping
├── static/               # CSS, Local Images & Assets
│   └── style.css         # Premium Design System
├── templates/            # HTML Views
│   ├── index.html        # Landing Page
│   └── scanner.html      # Smart Dashboard
└── requirements.txt      # Project Dependencies
```

## 🎯 PRD Alignment (Version 3.0)

This project strictly follows the **Sneaker Hunter AI Official PRD**:
- **Confidence Threshold**: 75% cutoff for identifying "Unsure" states.
- **Latency**: < 3 seconds report generation.
- **Accuracy**: > 95% identification rate for established silhouettes.

## 🤝 Contribution

We are continuously adding more models and reseller integrations. Feel free to open a PR!

---
*Built with ❤️ for the Indian Sneakerhead Community.*
