# Sentiment Analysis Model

**Note: This project is a work in progress and is not yet optimized or complete.**

This project aims to perform sentiment analysis on text data using quantum circuits and classical NLP techniques. Discover the potential of quantum computing in the realm of understanding human emotions in text.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sentiment analysis aims to determine the sentiment or emotion expressed in a piece of text. This project explores the integration of quantum circuits with sentiment analysis using the Qiskit library for quantum computing and NLTK library for natural language processing.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/watermelonich/quSentimentModel.git
    cd sentimanalysis
    ```

2. Create a virtual environment (recommended):

    ```
    python -m venv venv
    source venv/bin/activate        # On Windows: venv\Scripts\activate
    ```

3. Install the required packages within the virtual environment:

    ```
    pip install -r requirements.txt
    ```

## Dependencies

The following packages are required to run the sentiment analysis model. Be sure to install them within your virtual environment:

- `warnings`
- `matplotlib`
- `qiskit`
- `nltk`

For a detailed list of dependencies, check the [requirements.txt](requirements.txt) file.

## Usage

To use the sentiment analysis model, follow these steps:

1. Prepare your test data in a file named `testdata.txt`.

2. Activate your virtual environment:

    ```
    source venv/bin/activate            # On Windows: venv\Scripts\activate
    ```

3. Run the main script:

    ```
    python qusentan.py
    ```

   The analysis results will be saved in `testdata_output.txt`.

**Note:** The code includes a deprecation warning related to Qiskit-Aer. To suppress this warning, the `warnings` module has been used. Please refer to the code for details.

## Contributing

Contributions to this project are welcome! Feel free to open issues, submit pull requests, or provide feedback. However, as this project is not yet optimized or complete, please keep that in mind when contributing.

## License

This project is licensed under the [MIT License](LICENSE).
