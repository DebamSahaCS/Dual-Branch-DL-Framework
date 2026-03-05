**Paper Name: A Dual-Branch Deep Learning Framework for Emotion Recognition from EEG Signals**
**Journal Name**: Scientific Reports. 

**Abstract:** Mental health monitoring through emotion recognition plays an important role in early intervention and personalized healthcare
systems. Traditional EEG-based emotion recognition approaches have encountered significant limitations, including heavy
reliance on manual feature engineering, poor generalization across datasets, and computational complexity that restricts
real-world deployment. This study introduces a novel hybrid dual-branch deep learning architecture that integrates temporal
and spectral feature extraction for robust EEG-based emotion recognition, while minimizing preprocessing requirements.
The proposed framework integrates a Long Short-Term Memory (LSTM) network to capture temporal dependencies directly
from raw EEG signals, while concurrently leveraging Convolutional Neural Networks (CNNs) to extract spatial features from
Mel-Frequency Cepstral Coefficients (MFCC) representations. This architecture further incorporates innovative cross-modality
enhancement mechanisms, such as inverse MFCC computation and LSTM-to-MFCC projection, which facilitate bidirectional
feature learning between temporal and spectral domains. Subsequently, feature fusion is achieved through element-wise
multiplication and concatenation, and the integrated representations are classified using an Artificial Neural Network (ANN).
The evaluation has been conducted on three benchmark datasets: Brainwave EEG, WESAD, and SWELL, achieving
remarkable performance with accuracies of 96.49%, 99.99%, and 99.99%, respectively. The model has attained perfect
precision, recall, and F1-scores on the WESAD and SWELL datasets, setting new state-of-the-art standards. Comparative
analysis has demonstrated the method’s superiority over existing machine learning and deep learning techniques, while
preserving computational efficiency that supports real-time applications. These results have confirmed the framework’s strong
potential for practical use in mental health monitoring and affective computing.

**Proposed Methodology:**
<img width="1317" height="643" alt="image" src="https://github.com/user-attachments/assets/167dcec3-0a8c-4ccc-914e-e8c8fa832aec" />
