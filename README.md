# 🦠 Malaria Cell Detection using CNN

This project uses **Convolutional Neural Networks (CNNs)** to classify cell images as **Parasitized** or **Uninfected**, helping in the automated diagnosis of **Malaria** from microscopic blood smear images.

---

## 📂 Dataset

The dataset contains two classes of cell images:

- **Parasitized**: Images of cells infected with the malaria parasite.
- **Uninfected**: Images of healthy cells.

Dataset source: [https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria] 
Or if hosted locally, place it in a folder like: `cell_images/Parasitized`, `cell_images/Uninfected`

## ‼️ Note

The dataset have hidden folder named cell_images.Make sure to follow the code exactly if running on Kaggle.

---

## 🧠 Model

- Built using **TensorFlow** and **Keras**
- CNN architecture:
  - Multiple convolutional + max pooling layers
  - Fully connected dense layers
  - Binary output with sigmoid activation
- Accuracy & loss tracked across training and validation sets

---

## 📊 Evaluation

- Training/validation accuracy and loss plotted using `matplotlib`
- Confusion matrix, classification report used for performance evaluation

---

📁 Project Structure
<pre> Malaria-Cell-Detection/ │ ├── malaria.ipynb # Main Jupyter Notebook ├── requirements.txt # Dependencies for the project ├── LICENSE # Open-source license (MIT) ├── README.md # This file │ └── cell_images/ # Dataset folder (NIH Malaria dataset) ├── Parasitized/ └── Uninfected/ </pre>

## 🚀 How to Run

-jupyter notebook malaria.ipynb
-jupyter nbconvert --execute malaria.ipynb


---

📈 Sample Results
<img width="1209" height="492" alt="image" src="https://github.com/user-attachments/assets/40ccbd93-c9d8-4711-a40f-c8f5e1d840d4" />

🧑‍💻 Author
Mahin Alam
📧 https://github.com/MahinA1am
🔗 Project maintained with ❤️ using Python & Deep Learning

📜 License
This project is licensed under the MIT License.


```bash
pip install -r requirements.txt
