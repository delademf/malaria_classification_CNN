---

# Malaria Detection using Convolutional Neural Network (CNN)

## Overview

This project implements a Convolutional Neural Network (CNN) for the detection of malaria-infected cells. The model is trained on a dataset containing images of malaria-infected and uninfected cells. The CNN is designed for binary classification, where it predicts whether a given cell image is infected or uninfected.

## Project Structure

- **`CNN_Malaria_Detection.ipynb`:** Jupyter Notebook containing the code for training the CNN model.
- **`utils.py`:** Utility functions used in the notebook (if any).
- **`data/`:** Directory containing the dataset used for training. [Link to the dataset](https://github.com/laxmimerit/Malaria-Classification-Using-CNN.git).
- **`saved_models/`:** Directory to store the saved model files.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV (cv2)

Install the required dependencies using:

```bash
pip install tensorflow keras numpy matplotlib opencv-python
```

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Malaria-Detection-CNN.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd Malaria-Detection-CNN
   ```

3. **Open and Run the Jupyter Notebook:**
   ```bash
   jupyter notebook CNN_Malaria_Detection.ipynb
   ```

4. **Follow the Instructions in the Notebook:**
   - Run each cell in the notebook sequentially to train the CNN model.
   - Save the trained model in the `saved_models/` directory.

5. **Make Predictions on New Images:**
   - Use the provided example code for making predictions on new images.

## Model Evaluation

The model's performance can be assessed by examining the learning curves (accuracy and loss) in the notebook. Adjustments to the model architecture, hyperparameters, or dataset may be necessary for improved performance.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Dataset Source](https://github.com/laxmimerit/Malaria-Classification-Using-CNN.git)

---

