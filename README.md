# car_Detection
🚗 Car Detection Using YOLOv8

This project demonstrates how to build a car detection model using YOLOv8, covering the full workflow from dataset preparation to model training, evaluation, and testing on new images.

📌 Overview

Model: YOLOv8n (lightweight and fast for experimentation)

Task: Detect cars in images (single-class object detection)

Tools: Python, Ultralytics YOLO, KaggleHub, Google Colab, Matplotlib

📂 Repository Contents

car_detection.ipynb – training and inference notebook

config.yaml – YOLO dataset configuration

data/ – dataset structure (images + labels) or instructions for preparing it

sample_results/ – output examples from the trained model

requirements.txt – required dependencies

🚀 How to Run

Clone the repository:

git clone [https://github.com/your-username/your-repo.git](https://github.com/Ghena-A/car_Detection)


Install the required packages:

pip install -r requirements.txt


Open the notebook (car_detection.ipynb) in Google Colab or a local environment with GPU support.

Download the dataset from Kaggle using kagglehub, or place your YOLO-formatted dataset inside the data/ folder.

Run the notebook cells step-by-step to train the model and test detection results.

📊 Results

The trained YOLOv8 model achieves solid performance in detecting cars within the dataset.

Sample outputs (bounding boxes and predictions) are provided in the sample_results/ directory.

Performance metrics such as Precision–Recall and detection visuals are included in the notebook.

📝 Notes

GPU is recommended for training to reduce runtime.

You can fine-tune the model by adjusting parameters in the YAML config (image size, epochs, etc.).

The project can easily be extended to include more classes or deployed using Gradio or Hugging Face Spaces.

🤝 Contributions

Feel free to submit issues, suggestions, or pull requests to improve the project.
