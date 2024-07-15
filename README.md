# Machine Learning and Deep Learning Projects

## Overview
This repository contains various machine learning and deep learning projects. Each project is organized into separate directories and includes detailed explanations of the models used, data preprocessing steps, and results achieved.

## Project Structure
- **Diabetes.ipynb/**: This file contains a project to predict diabetes using classical machine learning techniques.
- **IsCat.ipynb/**: This file contains a project to predict if a photo is of a cat using deep learning techniques.

## Diabetes

### Overview
This project aims to predict diabetes based on various health indicators. The project uses the following tools and libraries:
- **Numpy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For data visualization.
- **KNeighborsClassifier**: For the initial machine learning model.
- **Cross-validation**: For improving the model's accuracy.

### Steps
1. **Data Preprocessing**:
    - Load the dataset using Pandas.
    - Clean and preprocess the data.
    - Visualize the data using Matplotlib.
  
2. **Model Training**:
    - Train a KNeighborsClassifier model.
    - Achieve an initial accuracy of 0.68.

3. **Model Improvement**:
    - Apply cross-validation to the model.
    - Improve the accuracy to 0.77.


## IsCat

### Overview
This project aims to predict whether a photo is of a cat using a deep learning model. The project uses the following tools and libraries:
- **ResNet34**: For the deep learning model.
- **fastai**: For simplifying the deep learning workflow.
- **ipywidgets**: For interactive widgets in Jupyter notebooks.
- **URLs.PETS**: For obtaining cat photos.

### Steps
1. **Data Collection**:
    - Download cat photos from URLs.PETS using fastai.

2. **Data Preprocessing**:
    - Use fastai to preprocess and augment the data.

3. **Model Training**:
    - Train a ResNet34 model using fastai.
    - Achieve accurate predictions on the validation set.



### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/dostonshernazarov/MachineLearning_models.git
    cd MachineLearning_models
    ```

2. Navigate to the project directory and run the Jupyter notebooks:
    ```bash
    jupyter notebook
    ```

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.


## Contact
For any inquiries or questions, please contact [dostonshernazarov989@gmail.com].
