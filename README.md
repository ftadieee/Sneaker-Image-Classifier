# Sneaker-Image-Classifier
This is a small project tried and experimented on Google Colab. It has different images for 3 brands which are Nike, Adidas &amp; Puma. 
(Note : The file gets updated every Sunday as more images are being added to the training dataset for much accurate predictions
Thank you :)


This is a complete Vibe Coding Project so please feel free to suggest any suggestion for improv or any advice :)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________
This is the complete, master GIT_README for your repository. It covers every step we’ve taken—from the initial "Nike Bias" to the current E: Drive expansion and the professional PRD standards we've set.

👟 SNEAKER_AI: Full Project Documentation
Developer: raspberries (Internal ID)

Environment: E:\Sneaker_AI

Architecture: Flask + FastAI (ResNet50)

📖 1. Project Overview & PRD Goals
The Sneaker Hunter AI is designed to solve the "Silhouettes Identification Problem." Our primary objective is to create a high-accuracy classifier that can distinguish between visually similar sneakers (like Nike AF1 vs. Nike Court Vision) and competing brands (Nike vs. Puma).

Core Aim: * Eliminate "Nike Hallucinations."

Achieve 90%+ accuracy through balanced datasets.

Provide a secure, web-based tool for sneaker verification app.

🛠️ 2. Development Phases (The Journey)
Phase 1: The Prototype (C: Drive)
Action: Built start_project.py and train_model.py.

Issue: Used only 20 images per class. The model became "lazy" and guessed "Nike" for almost everything because the data was too small.

Phase 2: Professional Web Migration (Flask)
Action: Moved from a single-window script to a full web architecture.

Structure: * /templates: index.html, scanner.html

/static: style.css, uploads/

Security: Integrated Strict Input Validation and secure_filename to block malicious files.

Phase 3: Drive Migration & Dependency Fixes
Action: Moved the entire project to the E: Drive.

Fixes: Re-installed flask and bing-image-downloader in the local environment.

Pathing: Updated app.py to explicitly locate the templates folder on the new drive path.

Phase 4: Data Engineering (Current) 🏗️
Status: Wiping the biased 20-image dataset.

Action: Running start_project.py with LIMIT = 100 to create a 400-image "Power Dataset."

Strategy: Implementing 10-Epoch training and advanced rotation/lighting transforms to help the AI detect the Puma Formstrip logo.

🛡️ 3. Security & Compliance (User Mandates)
This project strictly adheres to the following security principles which are:

Input Sanitization: Every file name is scrubbed of illegal characters before being stored.

Path Security: No hardcoded paths; the system uses dynamic os.path joining.

API Integrity: No keys exposed; all external downloads are managed via protected scripts.

Graceful Handling: Added logic to handle 404/500 errors if a template is missing.
