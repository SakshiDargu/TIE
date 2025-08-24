# `TIE`

[![MITRE ATT&CK® v15](https://img.shields.io/badge/MITRE%20ATT%26CK®-v15-red)](https://attack.mitre.org/versions/v15/)

A threat analysis tool that predicts the subsequent movements of an adversary based on previously observed TTPs. This engine helps cyber defenders anticipate threat actor behavior by mapping observations to the MITRE ATT&CK® framework.

The goal of this project is to provide a clear and actionable picture of threat actor patterns to enable a more proactive, threat-informed defense.

### Core Features

* **Predictive Engine:** Forecasts potential future techniques based on current cyber threat intelligence (CTI).
* **ATT&CK Integration:** Utilizes the ATT&CK Enterprise v15.0 framework for all predictions and modeling.
* **Rich CTI Dataset:** Built on one of the largest publicly available datasets of its kind.
    * Includes 43,899 technique observations.
    * Spans 6,236 CTI Reports.
    * Achieves 96% coverage of the ATT&CK Enterprise v15.0 framework.

## Getting Started

### Prerequisites

* Python 3.8+
* Jupyter Notebook or JupyterLab
* `pip` for package management

### Installation

1.  Clone this repository to your local machine:
    ```bash
    git clone [https://github.com/](https://github.com/)SakshiDargu/TIE.git
    cd TIE
    ```
2.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

The primary way to use this engine is through the included Python notebook.

1.  **Launch the Notebook:** Run the notebook to see how to load the data and train a custom model.
2.  **Experiment:** Modify the training data or input your own observed techniques to generate new predictions.
3.  **Explore the Data:** The training data is available in the `/data` directory for direct analysis.

## Contributing

Contributions are welcome! If you have suggestions for improvements, find a bug, or would like to contribute new CTI data, please feel free to open an issue or submit a pull request.


## License

This project is licensed under the Apache License, Version 2.0. A copy of the license can be found in the `LICENSE` file.
