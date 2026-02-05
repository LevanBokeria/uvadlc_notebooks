# UvA Deep Learning Tutorials

This repository contains Jupyter notebook tutorials for deep learning, originally created for the University of Amsterdam's Deep Learning courses.

**Original Repository**: https://github.com/phlippe/uvadlc_notebooks  
**Author**: Phillip Lippe

## Setup

### Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd <repository-name>
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

### GPU Support

For GPU support with PyTorch, visit [PyTorch's installation page](https://pytorch.org/get-started/locally/) to get the correct installation command for your CUDA version.

For JAX with GPU support:
```bash
pip install --upgrade "jax[cuda12_pip]" -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
```

## Repository Structure

```
tutorial_notebooks/
├── tutorial2/           # Introduction to PyTorch
├── tutorial3/           # Activation Functions
├── tutorial4/           # Optimization and Initialization
├── tutorial5/           # Inception, ResNet, DenseNet
├── tutorial6/           # Transformers and Multi-Head Attention
├── tutorial7/           # Graph Neural Networks
├── tutorial8/           # Deep Energy Models
├── tutorial9/           # Autoencoders
├── tutorial10/          # Adversarial Attacks
├── tutorial11/          # Normalizing Flows
├── tutorial12/          # Autoregressive Image Modeling
├── tutorial13/          # Bayesian Deep Learning
├── tutorial15/          # Vision Transformers
├── tutorial16/          # Meta Learning
├── tutorial17/          # Self-Supervised Learning (SimCLR)
├── DL2/                 # Deep Learning 2 tutorials
├── JAX/                 # JAX/Flax versions of tutorials
├── scaling/             # Model scaling tutorials
└── guide1-4/            # Various guides
```

## Running the Notebooks

Start Jupyter:
```bash
jupyter notebook
```

Then navigate to the tutorial you want to run.

## Notes

- Most tutorials include pre-trained models that will be automatically downloaded
- Tutorials are designed to run on CPU, but GPU acceleration is recommended for larger models
- Each tutorial is self-contained and can be run independently

## Citation

If you find the tutorials helpful and would like to cite them:
```bibtex
@misc{lippe2024uvadlc,
   title        = {{UvA Deep Learning Tutorials}},
   author       = {Phillip Lippe},
   year         = 2024,
   howpublished = {\url{https://uvadlc-notebooks.readthedocs.io/en/latest/}}
}
```

## License

See [LICENSE.md](LICENSE.md) for details.
