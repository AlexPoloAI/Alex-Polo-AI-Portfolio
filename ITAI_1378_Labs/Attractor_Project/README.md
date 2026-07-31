Attractor Project: Final Build
This repository contains one final proof of concept for ITAI 1378 course. My name is Alex Polozov.

What I Built
This system processes images and detects people who match the user's specific preferences. Visual input from folder '01_my_taste_profiles'. This code processes those pixels. Real output generates. This pipeline uses YOLO11x to crop people from photos. After that step, this system uses Qwen2-VL to analyze semantic features. I also implemented One-Class SVM to measure geometric distances between image vectors.

Changes From Blueprint
During development, I changed some initial plans. I wanted to use only One-Class SVM for recognition. I tested that model with small data. It worked well. Then I generated much synthetic data to test scaling. SVM failed (although it’s important to understand that we’re training the model not to recognize a person, but to recognize a user’s specific taste, which is sometimes subconscious). Synthetic images have perfect pixels and zero camera noise. They break that SVM boundary. Because of this problem, I added one multimodal JSON pipeline using Qwen2-VL. This language model understands semantic context. It ignores pixel noise. This new JSON pipeline scales much better and filters complex patterns.

Installation and Execution
You must install dependencies from requirements.txt file. Use one standard package manager. After installation, open notebooks/attractor_main.ipynb file. You can run every cell. This code requires one strong GPU to run neural networks. I use my RTX 5090.

Before running the program, it’s important to create the following folder structure:

01_my_taste_profiles
02_processed_pics
03_persons_pics
04_tmp_crops
05_results_JSON
06_results_SVM

Place the photos used to train the neural network to your taste in folder 1 (train), and place the test photos of various people in folder 3 (test), from which the neural network will select those that match your taste preferences.
