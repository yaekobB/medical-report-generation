# 🏥 Automatic Medical Report Generation

This project explores deep learning methods for generating medical reports from chest X-ray images using the **Indiana University Chest X-ray dataset**.

## 🧠 Architectures Implemented

1. **ResNet50 (Encoder) + GPT-2 (Decoder)** — PyTorch  
2. **DenseNet121 (Encoder) + LSTM (Decoder)** — TensorFlow

Both models are trained, evaluated, and include report samples.

---

## 📁 Project Structure

notebooks/

├── 01_resnet50_gpt2.ipynb # PyTorch: ResNet50 + GPT-2 (with output & evaluation)

├── 02_densenet121_lstm.ipynb # TensorFlow: DenseNet121 + LSTM (with output & evaluation)

└── 03_reference_gpt2_usage.py # Optional: GPT-2 reference/inference code


---

## 📊 Model Evaluation

Each notebook includes:
- **BLEU Scores**
- **ROUGE Metrics**
- **Generated medical reports**
- Visual and qualitative comparison of both architectures

---

## 🛠️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/medical-report-gen.git
   cd medical-report-gen

2. Install dependencies

   pip install torch tensorflow transformers matplotlib
3. Open the notebooks
Use Jupyter Notebook, Colab, or VSCode with Python support.

📦 Dataset
Dataset Name: Chest X-rays (Indiana University)

Kaggle Link: https://www.kaggle.com/datasets/raddar/chest-xrays-indiana-university

📌 Note: This dataset is not included in the repo. Download it from Kaggle and adjust the path in the notebook if needed.

📷 Example Output
Included in notebooks:

Sample generated reports

Evaluation scores

Output visualizations

📄 License
This project is open-sourced under the MIT License.

🙋‍♂️ Author
Yaekob — AI & Computer Science Student
📬 Feel free to reach out or open an issue with feedback or contributions!



---

Let me know if you'd like me to turn this into a README with badges, links to Colab, or sample image previews!
