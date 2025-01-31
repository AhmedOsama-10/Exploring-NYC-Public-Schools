# NYC High School SAT Analysis

This repository contains a Jupyter notebook that analyzes SAT scores of high schools in New York City. The analysis includes data manipulation, calculation of statistics, and visualization of results.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The purpose of this project is to analyze SAT scores of high schools in New York City. The analysis includes calculating total SAT scores, summarizing statistics by borough, and visualizing the results.

## Data

The dataset used in this analysis includes the following columns:
- `borough`: The borough where the school is located.
- `school_name`: The name of the school.
- `average_math`: The average math SAT score.
- `average_reading`: The average reading SAT score.
- `average_writing`: The average writing SAT score.

## Analysis

The analysis is performed in a Jupyter notebook and includes the following steps:
1. **Data Selection**: Selecting relevant columns for analysis.
2. **Total SAT Calculation**: Calculating the total SAT score for each school.
3. **Summary Statistics**: Calculating summary statistics (sum, min, max, median, std) for each borough.
4. **Borough with Largest Standard Deviation**: Identifying the borough with the largest standard deviation in SAT scores.

## Visualizations

The notebook includes the following visualizations:
1. **Top 10 Schools by Total SAT Score**: A bar chart showing the top 10 schools by their total SAT scores.
2. **Borough-wise SAT Statistics**: A bar chart showing the sum, min, max, median, and standard deviation of total SAT scores for each borough.
3. **Borough with Largest Standard Deviation**: A bar chart highlighting the borough with the largest standard deviation in SAT scores.

## Usage

To run the notebook, follow these steps:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nyc-high-school-sat-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nyc-high-school-sat-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Open the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
5. Run the cells in the notebook to perform the analysis and generate the visualizations.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
