# CGAN Faces - Gender Classification using Conditional GANs

This repository contains a Jupyter Notebook that implements a Conditional Generative Adversarial Network (CGAN) to generate facial images based on gender. The model is trained using the "Gender Classification Dataset" from Kaggle.

## Dataset

The notebook utilizes the [Gender Classification Dataset](https://www.kaggle.com/cashutosh/gender-classification-dataset), which contains a collection of images labeled by gender. The dataset is automatically downloaded and extracted using the Kaggle API.

## Prerequisites

Before running the notebook, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Kaggle API (configured with your credentials)

### Python Libraries

- `kaggle`
- `tensorflow`
- `keras`
- `numpy`
- `matplotlib`

You can install the required libraries using:

```bash
pip install kaggle tensorflow keras numpy matplotlib
```

## Running the Notebook
1. Clone the repository:
```bash
git clone https://github.com/your-username/cgan-faces.git
cd cgan-faces
```
2. Open the notebook
```bash
jupyter notebook cgan-faces.ipynb
```
3. Ensure your Kaggle API credentials are properly set up. The dataset will be downloaded automatically when you run the first cell of the notebook.
4. Execute the notebook cells to preprocess the dataset, define the CGAN model, and begin training.
## Notebook Contents
The notebook is organized as follows:

1. **Dataset Download:** The dataset is downloaded from Kaggle using the Kaggle API and unzipped for further processing.
2. **Data Preprocessing:** The images are resized, normalized, and split into training and validation sets.
3. **Model Architecture:** The Conditional GAN model is built using TensorFlow and Keras, where the generator and discriminator networks are defined.
4. **Training:** The model is trained to generate facial images conditioned on gender labels.
5. **Evaluation and Results:** Generated images are visualized, and the performance of the model is evaluated through various metrics.

## Example Output:
Below is an example of the generated facial images based on gender:
- Women
- ![image](https://github.com/user-attachments/assets/1e659293-71cc-4383-8d78-402d95db8e83)
- Men
- ![image](https://github.com/user-attachments/assets/dab92b78-5f7f-4e27-be26-dc0726bc45ff)

## Acknowledgements
- The project is inspired by the concept of [Conditional GANs (CGANs)](https://arxiv.org/pdf/1411.1784), as introduced by Mirza and Osindero (2014).
## Licenses
This project is licensed under the MIT License - see the LICENSE file for details.


