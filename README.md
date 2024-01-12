# Data Drift in Machine Learning

## Note
The code for this repository is currently under organization and refinement.

## Introduction
This repository is the official implementation of methods presented in "Efficiently Mitigating the Impact of Data Drift on Machine Learning Pipelines". It introduces a novel approach for managing data drift in machine learning models, focusing on identifying and addressing Data Distributions with Low Accuracy (DDLA).

## Method Overview
We employ decision trees to detect DDLAs in black-box models, integrating with active learning for effective model retraining. This combination allows for a more efficient response to data drift, ensuring sustained model performance.

## Code Directory Structure
- `dataset/`: Datasets used for testing and examples.
- `tests/`: Test scripts ensuring code reliability.
- `examples/`: Sample scripts for quick start.

## Dataset Overview
The code uses various real-world datas	ets to validate our approach. Each dataset is specifically selected to represent typical data drift scenarios in machine learning.

## Setup Instructions
### Software Requirements
- Torch version: 1.1.0
- Python version: 3.8
- CUDA version: 10.1

### Dependencies
These files, of cause, require some basic scientific computing python packages, e.g., numpy, sklearn and matplotlib. I recommend users to install python via Anaconda (python 3.8), which can be downloaded from https://www.anaconda.com/distribution/#download-section . If you have installed Anaconda, then you do not need to worry about these basic packages.

## Contributing
Contributions to improve the code or methods are welcome. Please refer to our contributing guidelines for more information.


## Contact
For any queries or collaboration requests, please contact sijie.dong@etu.u-paris.fr.

## Acknowledgements
Special thanks to all contributors and supporting institutions.




