

```
# ASL Recognition using Convolutional Neural Networks

This project aims to recognize American Sign Language (ASL) gestures using Convolutional Neural Networks (CNNs). The code provided trains a CNN model on an ASL dataset and evaluates its performance.

## Dataset

The ASL dataset used in this project contains images of ASL gestures representing letters and numbers. The dataset consists of 36 classes, including digits 0-9 and letters A-Z.

The dataset is organized in a directory structure where each class has its own subdirectory containing the corresponding images.



### Prerequisites

To run the code, you need the following dependencies:

- Python (3.6 or higher)
- TensorFlow (2.0 or higher)
- Matplotlib

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your_username/your_repository.git
   ```

2. Install the required dependencies:

   ```shell
   pip install tensorflow matplotlib
   ```

3. Download the ASL dataset and place it in the `asl_dataset` directory.

4. Open the code in your preferred Python development environment.

### Usage

1. Run the script to train the ASL recognition model:

   ```shell
   python main.py
   ```

2. The script will load the dataset, preprocess the images, define the CNN model, train it on the training set, and evaluate its performance on the test set.

3. Once the training is complete, the model's performance metrics, such as loss and accuracy, will be displayed.

4. You can modify the code to experiment with different hyperparameters, network architectures, or data augmentation techniques.

## Results

The trained model achieves an accuracy of X% on the test set. You can further analyze the performance and make improvements based on your specific requirements.


## Acknowledgments

- The ASL dataset used in this project was obtained from
- https://www.kaggle.com/datasets/grassknoted/asl-alphabet

```
