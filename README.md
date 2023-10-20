# movies: A Movie Recommendation System

## Table of Contents

1. [Introduction](#introduction)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Features](#features)
5. [Project Structure](#project-structure)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This project, called "moviez," aims to build a movie recommendation system using Collaborative Filtering with the Singular Value Decomposition (SVD) algorithm. The MovieLens dataset serves as the foundation for the model.

## Technologies

- Python 3.x
- pandas
- Flask
- Scikit-surprise

## Installation

### Clone the repository

```bash
git clone https://github.com/BrownieBrown/moviez.git
```

### Navigate to the project directory

```bash
cd moviez
```

### Install the required packages

```bash
pip install -r requirements.txt
```

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Collaborative Filtering using SVD
- Model evaluation using RMSE
- Flask API for real-time recommendations
- Simple Web Interface

## Project Structure

```plaintext
moviez/
│
├── data/
│   └── MovieLensDataset.csv
├── notebooks/
│   └── ExploratoryDataAnalysis.ipynb
├── src/
│   ├── preprocessing/
│   │   └── data_preprocessing.py
│   ├── model/
│   │   └── svd_collaborative.py
│   └── api/
│       ├── routes.py
│       └── app.py
├── tests/
│   ├── test_preprocessing.py
│   └── test_model.py
├── README.md
├── requirements.txt
└── .gitignore
```

## Usage

### Run the Flask API

Navigate to the `src/api/` directory and run:

```bash
python app.py
```

### Test the model

Navigate to the `tests/` directory and run:

```bash
python test_model.py
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
