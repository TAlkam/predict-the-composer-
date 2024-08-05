# Composer Classification Using Deep Learning

## Introduction

Music is a form of art that is ubiquitous and has a rich history. Different composers have created music with their unique styles and compositions. Identifying the composer of a particular piece of music can be challenging, especially for novice musicians or listeners. This project aims to use deep learning techniques to accurately identify the composer of a given piece of music.

## Objective

The primary objective of this project is to develop a deep learning model that can predict the composer of a given musical score accurately. The project aims to accomplish this by using two deep learning techniques: Long Short-Term Memory (LSTM) and Convolutional Neural Network (CNN).

## Dataset

The project uses a dataset consisting of musical scores from various composers. The dataset contains MIDI files of compositions from well-known classical composers like Bach, Beethoven, Chopin, Mozart, Schubert, etc. The dataset is labeled with the name of the composer for each score.

## Methodology

The project is implemented using the following steps:

1. **Data Collection**: MIDI files and corresponding labels (composers) are collected.
2. **Data Pre-processing**: Convert the musical scores into a format suitable for deep learning models, applying necessary data augmentation techniques.
3. **Feature Extraction**: Extract features such as note density, pitch range, average velocity, and average duration from the MIDI files.
4. **Model Building**: Develop a deep learning model using LSTM and CNN architectures to classify the musical scores according to the composer.
5. **Model Training**: Train the deep learning model using the pre-processed and feature-extracted data.
6. **Model Evaluation**: Evaluate the performance of the deep learning model using accuracy, precision, recall, and F1-score metrics.
7. **Model Optimization**: Optimize the deep learning model by fine-tuning hyperparameters using Keras Tuner.

## Files

- `Final_Team_Project_for_Deep_learning.ipynb`: The Jupyter notebook containing the complete code for data processing, feature extraction, model training, and evaluation.
- `README.md`: This file, providing an overview of the project.

## How to Run

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install the necessary dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

3. **Open the Jupyter notebook**:
    ```sh
    jupyter notebook Final_Team_Project_for_Deep_learning.ipynb
    ```

4. **Run the cells in the notebook** to execute the code step-by-step.

## Results

The final model achieves the following performance on the test dataset:

- **Test Accuracy**: 0.7778
- **Test Precision**: 0.7472
- **Test Recall**: 0.7778
- **Test F1-score**: 0.7392

These results demonstrate the effectiveness of using deep learning techniques for composer classification from musical scores.

## Conclusion

This project successfully implements a deep learning approach to classify composers based on musical scores. The combination of LSTM and CNN models, along with careful feature extraction and data preprocessing, allows for accurate composer identification.

## Future Work

Further improvements could be made by exploring additional features, utilizing more sophisticated models, or incorporating more diverse datasets to enhance the model's generalization capabilities.

## Acknowledgements

We would like to thank all the contributors and supporters who made this project possible.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

