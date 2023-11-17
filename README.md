# Zero-Knowledge Proof Simulation with Elliptic Curve Cryptography

This repository contains a Python-based simulation of a Zero-Knowledge Proof (ZKP) system using elliptic curve cryptography. It demonstrates a scenario where a borrower proves they meet certain credit score criteria to a lender without revealing their actual score.

## Overview

The project simulates a lending process where borrowers can prove that their credit score falls within certain categories (excellent, fair, poor, or not qualified) without disclosing the actual score. It uses elliptic curve digital signatures to create and verify proofs.

## Requirements

- Python 3.x
- Libraries: `ecdsa`, `ipywidgets`

## Installation

To set up the project, clone this repository and install the required Python libraries.

```
git clone <repository-url>
cd <repository-name>
pip install ecdsa ipywidgets
```


## Usage

Run the Jupyter Notebook (`ZKP-ZeroKnowledgeProofs.ipynb`) in a Jupyter environment or Google Colab. The notebook is divided into sections:

1. **Key Generation**: Generates cryptographic keys using elliptic curve cryptography.
2. **Proof Creation**: Allows a borrower to enter their credit score and generates a proof for their score category.
3. **Proof Verification**: Enables a lender to verify the borrower's proof without learning the actual credit score.
4. **Interactive UI**: Use sliders and buttons to simulate the process interactively.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License 

## Acknowledgements

This project is for educational purposes and demonstrates the basic concepts of Zero-Knowledge Proofs and elliptic curve cryptography in a simplified manner.
