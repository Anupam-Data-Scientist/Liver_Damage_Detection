# AI Liver Damage Detection 🧬🔬

A deep learning-based medical imaging project designed to detect liver damage from histopathology images using state-of-the-art CNN architectures.

---

## 📌 Objective

To accurately classify liver conditions (HCC, CCC, Normal) from histopathology images using deep learning models and assist medical professionals in early diagnosis.

---

## 🛠️ Tech Stack

- **Languages & Frameworks**: Python, TensorFlow, Keras
- **Models Used**: DenseNet, ResNet, YOLOv5 (for future detection-based tasks)
- **Libraries**: OpenCV, Matplotlib, NumPy, Pandas

---

## ⚙️ Project Workflow

1. **Data Collection & Organization**
   - Histopathology image data categorized into 3 classes: HCC, CCC, and Normal.

2. **Preprocessing**
   - Resized images, normalized pixel values, and applied augmentation techniques (rotation, flipping, zoom).

3. **Model Development**
   - Implemented and fine-tuned **DenseNet** model for high-accuracy classification.
   - Compared performance with ResNet and VGG16 using validation metrics.

4. **Evaluation**
   - Used metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
   - Achieved significant performance boost with DenseNet due to better feature reuse and reduced vanishing gradients.

5. **Future Scope**
   - Integration of YOLOv5 for detection/localization of liver damage areas.
   - Plan to deploy a lightweight interface for clinical use.

---

## 📊 Key Results

- ✅ DenseNet achieved the highest classification accuracy among tested models.
- 📈 Improved early detection capability by analyzing tissue-level image features.
- 🏥 Supports automated second-opinion diagnostics in healthcare.

---

## 📂 Project Structure

AI_Liver_Damage_Detection/
│
├── Dataset/ # Organized image folders (HCC, CCC, Normal)
├── Models/ # Scripts and saved weights for DenseNet, etc.
├── Preprocessing/ # Image normalization and augmentation
├── Visualizations/ # Evaluation plots and model insights
├── README.md # Project documentation


---

## ▶️ How to Run

1. Clone the repository  
```bash
git clone https://github.com/Anupam-Data-Scientist/AI_Liver_Damage_Detection.git
cd AI_Liver_Damage_Detection

2. Install Dependencies
pip install -r requirements.txt

3. Run model training
python Models/train_densenet.py
