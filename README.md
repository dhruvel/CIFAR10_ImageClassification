# CIFAR10_ImageClassification

This project involves building an image classification model using Xcode's ML Core tools and the CIFAR-10 dataset for training, testing, and validation.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to develop a machine learning model that can accurately classify images into one of the ten classes provided in the CIFAR-10 dataset. The model is built and trained using Xcode's ML Core tools.

## Dataset

The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class. The dataset is divided into 50,000 training images and 10,000 testing images.

Dataset Citation:

HNG BiqC. (2021). *CIFAR-10 Images Dataset*. Kaggle. Retrieved from [https://www.kaggle.com/datasets/hngbiquc/cifar10-images-dataset/data](https://www.kaggle.com/datasets/hngbiquc/cifar10-images-dataset/data)

## Installation

1. Ensure you have Xcode installed.

2. Clone the repository:
    ```bash
    git clone https://github.com/dhruvel/CIFAR10_ImageClassification.git
    cd CIFAR10_ImageClassification
    ```

3. Rename the directory to have a `.mlproj` extension for it to be discoverable by Xcode:
    ```bash
    cd ..
    mv CIFAR10_ImageClassification CIFAR10_ImageClassification.mlproj
    ```

## Usage

1. Prepare the dataset:
    - Download the CIFAR-10 dataset from Kaggle and place it in the appropriate directory.

2. Train the model further:
    - Open the `.mlproj` file in Xcode.
    - Download a Dataset from [Kaggle]{https://www.kaggle.com/} and train the model further to improve the accuracy
    - Run the training script to train the model on the CIFAR-10 dataset.

3. Test the model:
    - After training, use the testing script to evaluate the model's performance on the test set.


## Results

Once the model is trained, you can visualize the results and evaluate the performance using the provided evaluation scripts. The results will be saved in the results directory.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature/your-feature-name
    ```
3. Make your changes.
4. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
5. Push to the branch:
    ```bash
    git push origin feature/your-feature-name
    ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to open an issue if you have any questions or suggestions.
