# Sneaker-Image-Classifier
This is a small project tried and experimented on Google Colab. It has different images for 3 brands which are Nike, Adidas &amp; Puma. 
(Note : The file gets updated every Sunday as more images are being added to the training dataset for much accurate predictions
Thank you :)


This is a complete Vibe Coding Project so please feel free to suggest any suggestion for improv or any advice :)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________
📅 PHASE 1: The Birth of the Model
Initial Setup: Created the core scripts start_project.py and train_model.py.

Technology: FastAI (Deep Learning) using the ResNet50 neural network architecture.

The Problem: Started with a small test set (20 images/shoe). This caused the model to over-simplify and guess "Nike" for almost everything.

📅 PHASE 2: UI Evolution (Gradio to Flask)
Gradio Era: Built a quick-test interface. It worked but lacked professional features.

The Flask Migration: Based on the "Option B" decision, moved to a full web server architecture.

Directory Revamp: Created templates/ and static/ to house the website's HTML/CSS.

Security: Implemented Strict Input Validation and Secure Filename sanitization to protect the server from malicious uploads.

📅 PHASE 3: Environment & Path Troubleshooting
Drive Jump: Migrated the entire project to the E: drive to manage space and organization.

Dependency Fix: Resolved "Module Not Found" errors for flask and bing-image-downloader by correctly configuring the Anaconda environment on the new drive.

Path Correction: Solved the TemplateNotFound error by explicitly pointing Flask to the templates folder via the app.py configuration.

📅 PHASE 4: Data Engineering (Current)
Reset: Deleted the biased 20-image datasets.

Expansion: Currently running start_project.py with LIMIT = 100.

Next Action: Re-training the model for 10 Epochs with advanced data augmentation (rotation and lighting) to ensure the AI recognizes the Puma Formstrip.
