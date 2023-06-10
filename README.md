# Clean/Dirty Road Classification Dataset

This repository contains code and resources for a clean/dirty road classification project. The dataset used in this project is sourced from Kaggle and is available at [Clean/Dirty Road Classification Dataset](https://www.kaggle.com/datasets/faizalkarim/cleandirty-road-classification).

## Dataset Description

The Clean/Dirty Road Classification Dataset consists of images depicting roads categorized into two classes: clean and dirty. The images showcase various road conditions, including clean roads without any dirt or debris and dirty roads with visible dirt, garbage, or other forms of contamination.

The dataset contains the following files:

- `clear_dirty_street.ipynb`: Jupyter Notebook containing the code for the image classification project.
- `metadata.csv`: CSV file containing the image filenames and their corresponding labels (clean or dirty).
- `requirements.txt`: Text file listing the required dependencies to run the project code.

## Model Architecture and Accuracy

In this project, the VGG16 model is used for transfer learning to classify clean and dirty road images. The VGG16 model is pre-trained on a large dataset and has proven to be effective in image classification tasks. The project code fine-tunes the VGG16 model with the Clean/Dirty Road Classification Dataset to achieve accurate classification results.

After training the model, it achieved an impressive accuracy of 99.30% on the test set. This accuracy represents the model's ability to correctly classify clean and dirty road images.

## Getting Started

To get started with this project, please follow these steps:

1. Download the Clean/Dirty Road Classification Dataset from the Kaggle link provided above.
2. Clone this repository:
    
    ```
    git clone https://github.com/ahmedkltn/image-classification.git
    ```
    
- Set up the virtual environment (recommended):
    
    ```
    python -m venv env
    source env/bin/activate # For Linux/Mac
    .\env\Scripts\activate # For Windows
    ```
    
- Install the project dependencies:
    
    ```
    pip install -r requirements.txt
    ```
    
1. Run the `clear_dirty_street.ipynb` Jupyter Notebook to train the image classification model and evaluate its performance.

## Results and Further Customization

After running the code, you can explore the results and further customize the project. Feel free to modify the code, experiment with different parameters, and explore ways to improve the model's performance.

The trained model achieved an accuracy of 99.30%, indicating its effectiveness in classifying clean and dirty road images. You can apply this model to new road images to predict their cleanliness and use it for various road classification tasks.

## License

This project is licensed under the MIT License.