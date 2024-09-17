# Fine-Tuning Vision Transformer (ViT) Model on CIFAR-100 Dataset

This project fine-tunes a Vision Transformer (ViT) model for image classification on the CIFAR-100 dataset using the Hugging Face framework.
TensorBoard is utilized for visualizing different stages of the project, such as image samples, model architecture, training steps, and evaluation results.

## Setup

To begin, install the required dependencies by running:

```bash
pip install -r requirements.txt
```

## Optional: Start TensorBoard

It is recommended to launch TensorBoard to monitor the training process:

```bash
tensorboard --logdir logs/
```

Open [http://localhost:6006/](http://localhost:6006/) to view the TensorBoard dashboard.

## Running the Project
Execute the `FineTuningVitOnCIFAR100.ipynb` notebook and follow the results in TensorBoard.

## Output
I have included the results from my fine-tuning run in the `output-models` directory.
