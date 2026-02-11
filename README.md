# Navarasa-Based Multimodal Emotion Recognition

## Authors

**Risa Patil** (Primary Author), Soujanya Poojari, Apoorva Yallapurmath, Anushka Singh, Dr. Chinmayananda A, Dr. Rajashri Khanai, and Salma Shahpurkar

## Overview

This repository contains the implementation of a novel multimodal emotion recognition system based on the Navarasa framework. The research explores advanced techniques for recognizing emotions across multiple modalities.

## About

Navarasa (नवरस), derived from Sanskrit, refers to the nine fundamental emotions in Indian aesthetics. This work leverages this traditional framework to develop a comprehensive multimodal emotion recognition system.

##  Tools & Technologies Used

**Programming Language:** Python 3.12

**Deep Learning & ML:**
- PyTorch (Deep Learning Framework)
- Transformers (HuggingFace - BERT for text processing)
- Scikit-learn (Model evaluation, train/test split)
- AdamW Optimizer with Warmup + Cosine Annealing

**Audio Processing:**
- Whisper (OpenAI - Audio transcription)
- Librosa (MFCC feature extraction)
- FFmpeg (Audio extraction from video)

**Video/Image Processing:**
- OpenCV (Video and image processing)
- Decord (Efficient video frame extraction)

**Data Processing:**
- NumPy (Numerical computations)
- Pandas (Data manipulation)
- SciPy (Statistical functions)
- openpyxl (Excel file handling)

**Visualization:**
- Matplotlib
- Seaborn

**Development Environment:**
- Kaggle Notebook with GPU support

##  Model Performance

Preliminary results on benchmark datasets:

| Model | MSE | MAE | PCC | CCC |
|-------|-----|-----|-----|-----|
| ABMEN | 0.0090 | 0.0649 | 0.8653 | 0.8509 |
| MAMF-Net | 0.0338 | 0.1243 | 0.3190 | 0.1644 |
| IMAN-MAN | 7.2828 | 2.5531 | 0.6354 | 0.0331 |
| ACMAN | 0.0058 | 0.0460 | 0.9126 | 0.9072 |

*Note: Detailed results and comparisons will be available in the published paper.*

## Publication

This research is currently under review for publication. The complete implementation and detailed methodology will be made available upon acceptance.

## Citation

If you find this work useful, please cite our paper (citation will be updated upon publication):

`
[Citation pending publication]
`

## Contact

For inquiries regarding this research, please contact the authors through the institutional channels provided in the paper.

## License

The code and models will be released under an appropriate open-source license following publication.

---

*Note: This repository will be updated with the full implementation after the paper is published.*
