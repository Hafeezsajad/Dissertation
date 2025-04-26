# 📝 Multilingual Handwritten Text Recognition

##  Project Overview
This project focuses on developing a deep learning system for recognizing handwritten text across three categories:

- **Digits** (using the **MNIST** dataset)
- **English Words** (using the **IAM Handwriting** Dataset)
- **Arabic Characters** (using the **AHCD** dataset)

Separate models were built for each task, tailored to the challenges of each language and writing style.
The system uses **CNNs** for digit and Arabic character recognition and a **CNN-BiLSTM-CTC** architecture for English word recognition.

---

## 🛠️ Technologies Used
- **Programming Language:** Python 3.11
- **Frameworks:** TensorFlow, Keras
- **Libraries:** NumPy, Pandas, OpenCV, Matplotlib, Scikit-learn, Editdistance
- **Platforms:** Google Colab Pro (GPU), Visual Studio Code (local)
- **Version Control:** GitHub

---

## Datasets
- **MNIST:** Handwritten digits (0–9), grayscale (28×28 pixels)
- **IAM Handwriting Dataset:** English cursive handwriting
- **AHCD:** Arabic handwritten characters (28 alphabet classes)

---

## How to Run the Code

1. **Clone the repository:**
    ```bash
    git clone <your-repo-link>
    ```

2. **Install required packages:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Open the notebooks:**
    - `MNIST.ipynb` — Digit Recognition
    - `Final OCR.ipynb` — English Word Recognition
    - `Arabic handwritten.ipynb` — Arabic Character Recognition

4. **Train and evaluate** by running all cells in the notebook.

---

## 📈 Evaluation Metrics
- **Accuracy**
- **Character Error Rate (CER)**
- **Word Error Rate (WER)**
- **Confusion Matrices**

---

## Applications
- Digitizing historical handwritten documents
- Real-time transcription of handwritten notes
- Language learning tools for English and Arabic
- Accessibility tools for converting handwriting into editable text

---

## Contact
For any questions or collaborations, feel free to reach out!


