# Top-k Training of GANs: Improving GAN Performance by Throwing Away Bad Samples

This repository contains a Jupyter Notebook that demonstrates the reimplementation of the paper "Top-k Training of GANs: Improving GAN Performance by Throwing Away Bad Samples" in PyTorch. The paper introduces a novel training method for Generative Adversarial Networks (GANs) that focuses on discarding poor-quality samples during the training process to enhance the overall performance.

## Paper Reference

If you use this code or find it helpful, please consider citing the original [paper](https://arxiv.org/abs/2002.06224)


## Getting Started

To get started with this code, follow these steps:

1. Clone this repository:

'git clone https://github.com/LucasDedieu/top-k-gan-training.git'

2. Install the required dependencies. We recommend using a virtual environment:

cd top-k-gan-training
python -m venv env
source env/bin/activate (Unix) or env\Scripts\activate (Windows)
pip install -r requirements.txt

3. Launch the Jupyter Notebook:

4. Open the `Top-k-GAN-Training.ipynb` notebook and execute the code cells to observe the reimplementation and experiment with different settings.

## Results

The Jupyter Notebook provides a step-by-step explanation of the top-k training method for GANs described in the paper. It includes code for training and evaluating the GAN model using the CIFAR dataset. The results, including quantitative metrics and generated samples, will be displayed during the execution of the notebook.

## Contributing

Contributions to this project are welcome. If you find any issues or want to propose enhancements, please submit a pull request or open an issue in this repository.



