# EEG-Based Prosthetic Control System

This project focuses on developing a system for controlling prosthetic hand movements using EEG (electroencephalography) signals. It explores Brain-Computer Interface (BCI) techniques, aiming to help individuals with motor disabilities achieve more intuitive and efficient prosthetic control.

---

## Project Overview

- **Goal**: Classify EEG signals to detect the intention of hand movement (rest, left, right).
- **Approach**:
  - Data source: EEG Motor Movement/Imagery Dataset from PhysioNet.
  - Pre-processing: Band-pass filtering, normalization, artifact removal, selection of relevant EEG channels (FC5, FC3, FC1, FCz).
  - Modeling: Convolutional Neural Networks (CNN) built in PyTorch, tested with various architectures and optimizations.
  - Evaluation: Accuracy, precision, recall, f1-score, confusion matrices.

---

## Technologies Used

- Python (NumPy, SciPy, PyTorch)
- Jupyter Notebook
- EEG signal analysis (STFT, Welch method)
- Machine learning (CNNs, dropout, learning rate schedulers)

---

## Results

- Best accuracy: ~60% using a simple CNN architecture.
- More complex models with additional layers and optimizations sometimes suffered from overfitting.
- Future improvements: advanced feature extraction, data augmentation, hybrid CNN + RNN models, testing on real-time data.

---

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/carlabarastean/eeg-prosthetic-control.git
   ```

2. Set up the environment:
   ```
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:
   ```
   jupyter notebook EEG_Control.ipynb
   ```

---

## Future Directions

- Implement data augmentation techniques to balance class distributions.
- Test hybrid CNN-RNN models for better temporal feature capture.
- Collect or use larger, balanced datasets.
- Integrate system with real-time prosthetic devices.

---

## Contact

For more details or collaboration:
- Email: carlabarastean@gmail.com
- LinkedIn: [linkedin.com/in/carla-barastean-621326269](https://www.linkedin.com/in/carla-barastean-621326269)

Thank you for visiting this project!
