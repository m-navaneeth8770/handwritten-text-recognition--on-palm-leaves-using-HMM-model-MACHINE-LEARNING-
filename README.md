📜 Handwritten Text Recognition on Palm Leaves using HMM
This project explores a segmentation-free handwritten text recognition system applied to ancient palm-leaf manuscripts. The goal is to preserve and digitize historic scripts using a Hidden Markov Model (HMM)-based machine learning approach.

🎯 Objective
To build a machine learning pipeline capable of recognizing and decoding handwritten text from palm-leaf images using zone-based feature extraction and HMM sequence modeling, without requiring character segmentation.

🧠 Methodology
1. Preprocessing
Image Binarization – Convert grayscale images into binary to highlight strokes.

Contour Detection – Extract structural outlines of handwritten text.

Normalization – Resize and align characters for consistent input formatting.

2. Feature Extraction
Zone-based partitioning of characters into smaller segments for detailed pattern representation.

Constructed feature vectors suitable for time-series modeling using HMMs.

3. HMM Model Training
Designed a character-level Hidden Markov Model.

Trained the model using extracted feature vectors.

Recognized handwritten sequences by calculating the most probable state sequence.

🔍 Note: The final model output is still under evaluation; current results involve preprocessing and pipeline setup.

🛠 Tech Stack
Language: Python

Libraries: OpenCV, NumPy, Scikit-learn, hmmlearn

Techniques: Image Processing, Feature Engineering, Hidden Markov Models (HMM)
