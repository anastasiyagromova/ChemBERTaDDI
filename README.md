# ChemBERTaDDI: Transforming Drug-Drug Interaction Prediction with Transformers and Clinical Insights

## Description
The problem of polypharmacy arises when two or more drugs taken in combination cause adverse side effects, even when the use of the drugs individually causes no harm. Drug-drug interactions (DDIs) are a major cause of these reactions, contributing to increased morbidity and mortality. As the potential for harmful DDI grows exponentially, the prediction of drug-drug interactions is increasingly critical for patient safety and effective healthcare management.

In this study, we develop the **ChemBERTaDDI** framework, which effectively combines clinical domain data, represented by the mono side-effect features with the enriched chemical molecular representations derived from *ChemBERTa-77M-MLM*, a transformer-based language model.

## Installation

### Requirements
Ensure you have Python 3 installed.
Install the required dependencies using the provided `requirements.txt` file.

```bash
pip install -r requirements.txt

```

### Dependencies
```bash
scikit-learn
matplotlib
tensorflow==2.12.0
keras
keras-tuner
torch
transformers==4.46.2
```

### Usage
```bash
jupyter notebook ChemBERTa.ipynb
```

### Citation
If you use the code or datasets in this repository, please cite our work as follows:

```bibtex
@article{gromova2024chembertaddi,
  title={ChemBERTaDDI: Transforming Drug-Drug Interaction Prediction with Transformers and Clinical Insights},
  author={Gromova, Anastasiya and Maida, Anthony},
  journal={bioRxiv},
  year={2024},
  doi={10.1101/XXXXX}
}