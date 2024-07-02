# EEG-Signal-classification

## Project Description

This repository contains the code and documentation for the data science project developed as part of the course at the Polytechnic University of Madrid. The main objective of the project is to perform the classification of motor imagery EEG signals in patients with high uncertainty using a Spectral Transformer.

## Repository Structure

- `project.ipynb`: Jupyter Notebook file that contains the complete project explained step by step.
- `utils.py`: File with utility functions required for the notebook.
- `models.py`: Implementation of ATCNet and Spectral Transformer.

## Usage

To run the project, follow these steps:

1. Install the necessary dependencies: `pip install -r requirements.txt` (make sure you have the required libraries).
2. Open and run the `notebook.ipynb` in your Jupyter environment.

> [!IMPORTANT]
> Make sure you have download the BCI Competition IV 2a Dataset and it is added to your folder.


## References

- **ATCNet Paper**: Link to the [ATCNet paper](https://ieeexplore.ieee.org/document/9852687) and their [original code](https://github.com/Altaheri/EEG-ATCNet/tree/main)
- **Spectral Transformer Paper**: [Link to the Spectral Transformer paper](https://www.sciencedirect.com/science/article/abs/pii/S1746809423005633)

## Datasets

This project uses the following datasets:

- **PhysioNet EEGMMIDB**: Link to the [dataset](https://www.physionet.org/content/eegmmidb/1.0.0/)
- **BCI Competition IV 2a**: Link to the [dataset](http://bnci-horizon-2020.eu/database/data-sets) and to the [documentation](https://lampx.tugraz.at/~bci/database/001-2014/description.pdf)




