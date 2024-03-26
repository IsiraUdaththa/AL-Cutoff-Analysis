# Sri Lanka A/L Cutoff Analysis

This repository contains analysis and data regarding the minimum "Z" scores for selection to various courses of study at universities in Sri Lanka for various academic years, based on the results of the G.C.E. (Advanced Level) Examination (after re-scrutiny).

# Data

All pdfs are Downloaded from University Grants Commission

Minimum "Z" Scores for selection to various Courses of Study of Universities, in respect of each district,
- https://ugc.ac.lk/downloads/admissions/cutoff_2023
- https://ugc.ac.lk/downloads/admissions/cutoff_2022
- https://ugc.ac.lk/downloads/admissions/cutoff_2021
- https://ugc.ac.lk/downloads/admissions/cutoff_2020
- https://ugc.ac.lk/downloads/admissions/cutoff_2019
- https://ugc.ac.lk/downloads/admissions/cutoff_2016

Then Renamed for our convenience.

# Process 

1. All pdf transformed to csv using Tabula
2. Bring all to python and perform EDA
3. Try to simple algorithm to find what courses will be selected for given mark
4. Adding more analysis, visualizations, or updating the data.
5. Your ideas are welcome here. 



Certainly! Below is an updated version of the Readme.md file including instructions on how to install basic data science libraries and JupyterLab:


## Installation

To run the analysis notebook and utilize the data, follow these steps to install the necessary dependencies:

1. **Install Python**: Ensure you have Python installed on your system. You can download it from the official Python website: [python.org](https://www.python.org/downloads/).

2. **Install JupyterLab**: JupyterLab is an interactive development environment for working with notebooks, code, and data. You can install it using pip by running the following command in your terminal or command prompt:

    ```
    pip install jupyterlab
    ```

3. **Install Data Science Libraries**: Install the essential data science libraries using pip. Here are some common ones:

    ```
    pip install numpy pandas matplotlib seaborn scipy scikit-learn 
    ```

4. **Verify Installation**: After installing, you can verify the installation of these libraries by importing them in a Python script or Jupyter Notebook.

5. **Start JupyterLab**: Once everything is installed, you can start JupyterLab by running the following command in your terminal or command prompt:

    ```
    jupyter lab
    ```

    This command will launch JupyterLab in your default web browser. From there, you can create new notebooks and start working on your data science projects.

## Contributors

- [Isira Rathanayke](https://github.com/IsiraUdaththa)
- [Ravindu Weerakoon](https://github.com/theirusername)

---

Feel free to contribute to this repository by adding more analysis, visualizations, or updating the data.