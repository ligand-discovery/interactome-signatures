# Interactome Signatures
Interactome signature modeling for the [Ligand Discovery](https://ligand-discovery.ai) project. This repository contains two [Jupyter Notebooks](https://jupyter.org/) used to generate interactome signatures from fully-functionalized fragment screening data and validate accuracy of associated predictive models.

## Usage

* [Download](https://ligand-discovery.s3.eu-central-1.amazonaws.com/interactome-signatures/data.zip) and unzip the `data` directory in the current folder
* Open the `notebooks/InteractomeSignatures.ipynb` notebook and install the necessary dependencies, as specified in the first executable cell.
* If you want to validate the predictive models, execute `notebooks/Validations.ipynb`.
* A `results` folder will be generated. If you want to avoid the previous steps, you directly can [download precalculated](https://ligand-discovery.s3.eu-central-1.amazonaws.com/interactome-signatures/results.zip) results.
