# CNN Nail Classification

This repository contains a Convolutional Neural Network (CNN) designed to classify nail images into two categories:

1. **Healthy Nails**
2. **Nail Melanoma**

The model uses an image dataset to train and evaluate the performance of the classifier.

## Features

- **Deep Learning Architecture:** Leveraging CNN for image classification. In the future, it will use the VGG16 architecture
- **Evaluation Metrics:** Accuracy and loss. In the future, it will include precision, recall, F1-score, and confusion matrix.
- **Saving and Loading Models:** Ability to compile, save, and load models. Models will be stored in `/Models` folder

---

## Requirements

Ensure you have the following installed on your system:

- Python 3.8+
- Jupyter Notebook
- `venv` module

---

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/cnn-nail.git  
   cd cnn-nail  
   ```

2. **Setup the Virtual Engironment:**

    ```bash
    python -m venv cnn-nail-env  
    source cnn-nail-env/bin/activate   # On Windows cnn-nail-env\Scripts\activate  
    ```

3. **Start Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```
4. **Open the .ipynb Files:**

    - Navigate to the .ipynb files in the Jupyter interface and open them.
    - Follow the cells in order to preprocess data, train the model, and evaluate it.

## License
This project is licensed under the MIT License.

