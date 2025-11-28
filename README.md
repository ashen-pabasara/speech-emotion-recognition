# Speech Emotion Recognition using CNN
This project implements a Deep Learning model to classify human emotions from speech audio recordings. Using the Toronto Emotional Speech Set (TESS), the model extracts Mel Frequency Cepstral Coefficients (MFCCs) features and classifies them into seven distinct emotional categories using a Convolutional Neural Network (CNN).

# 📌 Project Overview

- Goal: To design a neural network that identifies a speaker's emotional state from audio.
- Method: Audio preprocessing -> Feature Extraction (MFCC) -> CNN Classification.
- Performance: Achieved a test accuracy of **99.64%.**

# 📂 Dataset

The project uses the Toronto Emotional Speech Set (TESS).
- Source: [TESS Dataset](https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP2/E8H2MF)
- Content: 2,800 audio files (WAV format).
- Speakers: Two actresses (aged 26 and 64).
- Emotions Classified:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Neutral
  - Pleasant Surprise
  - Sad

# ⚙️ Methodology

- Exploratory Data Analysis (EDA): Analysis of waveforms and spectrograms to understand frequency distributions across different emotions.
- Feature Extraction: Extraction of MFCC features to represent the spectral energy of speech signals.
- Model Architecture: A Convolutional Neural Network (CNN) trained on the extracted features.
- Training:
  - Epochs: 25
  - Batch Size: 32
 
# 📊 Results

- Final Accuracy: 99.64%
- Confusion Matrix: The model shows strong classification performance with minimal misclassification between similar emotional tones.

# 🛠️ Installation & Requirements

To run this project locally, you will need Python and the following libraries:

```
pip install kaggle librosa soundfile tensorflow scikit-learn matplotlib
```
# 🚀 Usage

1. Clone the repository:
```
git clone https://github.com/ashen-pabasara/speech-emotion-recognition.git
```
# 📄 Reference

> M. K. Pichora-Fuller and K. Dupuis, “Toronto emotional speech set (TESS).” Borealis, Feb. 13, 2020. 
doi: 10.5683/SP2/E8H2MF.

---------
*This project was developed as part of a study on Speech Emotion Recognition.*
