# Object-Recogniton-in-natural-scenes-using-combined-text-and-images-features
Detecting data elements using both visual and embedded text elements 
# 🌄 Natural Scene Recognition using Convolutional Neural Networks
 Description
This project is focused on the classification of natural scene images into six categories: buildings, forest, glaciers, mountains and streets. It uses a convolutional neural network (CNN) model trained on a condensed version of the Intel Image Classification Dataset and features a web interface built with streamlit.
Project structure
├── dataset/
│   └── (image folders: buildings, forest, glacier, etc.)
├── train.py
├── app.py
├── my_model.h5
└── README.md
 Tools & Libraries Used
- Python 3.x
- TensorFlow & Keras
- Scikit-learn
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Streamlit (for the web app)
Model Architecture
- 4 Convolutional Layers
- LeakyReLU activation
- MaxPooling layers
- Fully connected Dense layers with Dropout
- Softmax output layer for classification
How to Run the Project
Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
instal required libaries 
pip install -r requirements.txt
If you don’t have a requirements.txt, manually install the major ones:
pip install tensorflow scikit-learn numpy matplotlib pillow streamlit
Train the model:
python train.py
launch the web app
streamlit run app.py
Then open your browser and go to:
http://localhost:8501

Upload a .jpg image and it will predict which natural scene category it belongs to.
Model Performance (After 10 Epochs)
	•	Training Accuracy: 83.18%
	•	Validation Accuracy: 78.53%
	•	Precision, Recall & F1-score: 80%–90%+ across all classes
Contact

Daniel Chibuzor
Email: dchibuzor98@gmail.com
GitHub: @daniel5566-star
