# Distracted Driver Models Analysis

This repository contains Jupyter Notebooks for building, training, and analyzing various deep learning models for distracted driver detection. The primary goal is to classify images of drivers into different categories of distraction.

## Dataset

The models in this project are likely trained on the [State Farm Distracted Driver Detection](https://www.kaggle.com/c/state-farm-distracted-driver-detection) dataset. Please download the dataset and place it in a `data/` directory within the repository.

The dataset consists of 2D dashboard camera images, which are categorized into 10 classes:
- `c0`: safe driving
- `c1`: texting - right
- `c2`: talking on the phone - right
- `c3`: texting - left
- `c4`: talking on the phone - left
- `c5`: operating the radio
- `c6`: drinking
- `c7`: reaching behind
- `c8`: hair and makeup
- `c9`: talking to passenger

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

This project requires Python 3.x and the libraries listed in the `requirements.txt` file.

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/rithinnagaraj/distracted-driver-models-analysis.git
    ```
2.  Navigate to the project directory
    ```sh
    cd distracted-driver-models-analysis
    ```
3.  Create a virtual environment (recommended)
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
4.  Install the required packages
    ```sh
    pip install -r requirements.txt
    ```

## Usage

The core of this project is within the Jupyter Notebooks. To explore the project:

1.  Launch Jupyter Notebook or JupyterLab:
    ```sh
    jupyter notebook
    ```
    or
    ```sh
    jupyter lab
    ```
2.  Open the notebooks to see the data preprocessing, model building, training, and evaluation steps.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.