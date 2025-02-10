# About the Project
Transfer Learning is a powerful technique that allows reusing models previously trained on large datasets to solve new problems. In this project, we apply this approach to classify images of cats and dogs using the VGG16 network.

- Model Used: VGG16 (pre-trained on ImageNet)
- Dataset: Kaggle - Cats vs Dogs
- Framework: TensorFlow / Keras
- Objective: Train an efficient model and perform tests on real images
- Environment: Google Colab

## Project Structure

- `data/`: Contains the cat and dog image dataset.
- `notebooks/`: Jupyter Notebooks with the model training and evaluation code.
- `models/`: Trained models and saved weights.
- `README.md`: This file.

## Download the Pre-trained Model

Due to GitHub's file size limits, the trained model is hosted on Google Drive. You can download it from the link below:

**[Download modelo_treinado.keras](https://drive.google.com/file/d/1dJ1l0xfFzXnR-7zjWKbD71WM8tGxVQQ6/view?usp=sharing)**

After downloading, place the file in the `models/` folder.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/tezougo/Transfer-Learning-Machine-Learning-Bootcamp.git
cd your-repository
```

# Problems Faced and Solutions

## Oscillations in val_accuracy

- Implementation of ReduceLROnPlateau to adjust the learning rate.

## Overfitting in the Last Epochs

- Use of Dropout (Dropout(0.5)) and EarlyStopping (patience=5).

## Difficulty in Individual Predictions

- Function load_and_predict() to test the model on new images.

# Technologies Used 🚀
- TensorFlow/Keras: For building, training, and evaluating deep learning models.
- Matplotlib: Visualization of training metrics like accuracy and loss.
- NumPy: Efficient numerical computations, especially for handling arrays.
- Pandas: Data manipulation and analysis (used in data preprocessing stages).
- Google Colab: Cloud environment for running the notebook with GPU acceleration.
- Google Drive: For hosting large model files that exceed GitHub's file size limits.

# Contributions 🤝
If you want to contribute, follow these steps:

- Fork the repository
- Create a branch (git checkout -b feature-nova)
- Commit your changes (git commit -m 'Add new feature')
- Make a Push (git push origin feature-nova)
- Open a Pull Request

# Licença 📜
Este projeto está licenciado sob a MIT License.
