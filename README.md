# Sneaker-Image-Classifier
This is a small project tried and experimented on Google Colab. It has different images for 3 brands which are Nike, Adidas &amp; Puma. 
(Note : The file gets updated every Sunday as more images are being added to the training dataset for much accurate predictions
Thank you :)


This is a complete Vibe Coding Project so please feel free to suggest any suggestion for improv or any advice :)
_____________________________________________________________________________________________________________________________________________________________________________________________________________________________
👟 Sneaker Classifier AI Project
📅 Progress Report: Ground Zero to Training
Status: Phase 2 (Training) In Progress

🚀 Phase 1: Environment & Data Architecture
Infrastructure Setup: Successfully migrated project operations to the E: Drive to optimize storage and maintain a clean system environment.

Environment Configuration: Created a dedicated Conda environment (sneakers) with Python and PyTorch integration.

Secure Data Acquisition: * Developed a custom Python script (start_project.py) to bypass browser-based "Localhost" errors.

Implemented OWASP-aligned sanitization to handle folder naming and input validation.

Successfully scraped and organized 80+ high-quality images of four specific sneaker classes:

Nike Air Force 1

Nike Court Vision

Adidas Superstar

Puma Suede

🧠 Phase 2: Model Training (Current Milestone)
Hardware Acceleration: Configured the training pipeline to utilize the local NVIDIA RTX 3050 GPU via CUDA.

Custom Training Engine: * Developed train_model.py using the fastai and PyTorch frameworks.

Implemented a "Training from Scratch" approach to bypass corrupted pre-trained weight downloads and ensure local stability.

Integrated Data Augmentation (flips, rotations, and zooms) to improve model generalization with a small dataset.

Training Execution: Currently running 10 epochs of deep learning training.

🛠️ Technical Stack
Language: Python 3.x

Libraries: PyTorch, Fastai, Torchvision

Storage: 500GB E: Drive Partition

Hardware: NVIDIA GeForce RTX 3050 Laptop GPU

⏭️ Next Steps
Verify the generation of the sneaker_model.pkl "Brain" file.

Deploy the model using Gradio (Anti-Gravity) for a web-based user interface.

Test the AI with real-world sneaker photos.
