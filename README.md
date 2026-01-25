# Sneaker-Image-Classifier
This is a small project tried and experimented on Google Colab. It has different images for 3 brands which are Nike, Adidas &amp; Puma. 
(Note : The file gets updated every Sunday as more images are being added to the training dataset for much accurate predictions
Thank you :)


This is a complete Vibe Coding Project so please feel free to suggest any suggestion for improv or any advice :)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________
👟 Sneaker Classifier AI (Ground Zero)
A localized deep learning project built on Python, PyTorch, and fastai, utilizing an NVIDIA RTX 3050 for training and Gradio for deployment.

📊 Project Milestones
1. Environment & Data Architecture
Hardware Localization: Project established on a dedicated secondary partition (E:\Sneaker_AI) to maintain system performance and storage efficiency.

Conda Environment: Configured a isolated sneakers environment with CUDA support for GPU acceleration.

Scraping Engine: Developed a robust image scraper to bypass browser limitations, successfully gathering a dataset of:

Nike Air Force 1

Nike Court Vision

Adidas Superstar

Puma Suede

2. Secure Data Pipeline
OWASP Alignment: Implemented strict input validation to ensure only valid image formats (.jpg, .png) are processed.

Sanitization: Automated folder and file naming to prevent path injection and maintain "Ground Zero" cleanliness.

Data Augmentation: Applied random flips, rotations, and zooms during the loading phase to maximize model accuracy from a small initial dataset.

3. Model Training (RTX 3050)
Architecture: Utilized the ResNet34 Convolutional Neural Network (CNN).

Local Optimization: Executed a 10-epoch "training from scratch" cycle to ensure stability on the laptop GPU and avoid corrupted external weight downloads.

Result: Generated a high-performance model export file: sneaker_model.pkl.

4. Deployment (Anti-Gravity Interface)
Web UI: Developed a "Drag & Drop" interface using Gradio for real-time inference.

Stable Inference Mode: Configured the application to run inference on the CPU to ensure 100% web-server stability and prevent GPU timeouts.

Verified Performance: Successfully classified unseen sneaker images with real-time confidence scoring.

🛡️ Security & Constraints
Validation: All public-facing functions include schema-based type checks and input sanitization.

Hardware: NVIDIA GeForce RTX 3050 (Laptop GPU).

Environment: Localhost deployment only.

🚀 How to Run
conda activate sneakers

python app.py

Navigate to http://127.0.0.1:7860 in your web browser.
