# Model of the circuit for generating song and vibration in _Drosophila_

Code for

_A neural circuit for context-dependent multimodal signaling in Drosophila_  
Elsa Steinfath, Afshin Khalili, Melanie Stenger, Bjarne L. Schultze, Sarath Nair Ravindran, Kimia Alizadeh, Jan Clemens  
[preprint](https://doi.org/10.1101/2024.12.04.625245)

## Installation
Install anaconda/miniconda/[miniforge](https://github.com/conda-forge/miniforge?tab=readme-ov-file) and then create an environment with the required packages:
```shell
conda create numba numpy matplotlib ipykernel jupyterlab tqdm scipy flammkuchen -c conda-forge -n vib_model -y
```
## Demo
The notebook `demo.ipynb` will run the model on example inputs and generate plots. Expected results are show in [demo.pdf](demo.pdf).

