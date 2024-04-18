# neural-network-challenge-1
### Doug Francis
### Date: 4/17/2024
### Subject: For ASU Artificial Intelligence Course Work. Modeule 18. Due 4/18/2024

## About The Project
The coding and TensorFlow project is to model Student loan repayment data to develop a model predicting student loan repayment. That is the coding portion of the project. The project also had some questions that needed a write up regarding a student loan recommendation system, from the perspective of the student. 

## Location of the Code and Write Up

The file is in the root directory of the Git repository. The file name is "student_loans_with_deep_learning.ipynb". The write up for the student loan recommendation system is in the same Jupyter notebook as the code itself, at the end of the file.

## Getting Started

The steps below should get you started to get this project up and running on your local machine.

### Prerequisites

The following are prerequisites for this project. Instructions for pip installation are provided for each of the packages.

* Python - This project was created using Python version 3.11.5. Package compatability has not been tested with other versions of Python. See https://www.digitalocean.com/community/tutorials/install-python-windows-10 as a reference for Python installation.


* pandas (my version is 2.0.3)
  ```sh
  pip install pandas
  ```
* tensorflow (my version is 2.13.1)
  ```sh
  pip install tensorflow[and-cuda] - if using a compatable GPU

  or 

  pip install tensorflow-cpu - if using only your cpu
  ```
* sklearn (my version is 1.4.1.post1)
  ```sh
  pip install -U scikit-learn
  Note: scikit-lean installation encourages the use of a virtual environment. See https://scikit-learn.org/stable/install.html
  ```
* numpy (my version is 1.24.3)
  ```sh
  pip install numpy
  ```
* keras (my version is 2.13.1)
  ```sh
  keras will be automatically installed when you install tensorflow. While it can be installed separately, 
  ```

### Installation and Running

_In addition to setting up Python and the required packages, perform the following steps._

1. Clone the repository on your local machine
   ```sh
   git clone https://github.com/DougInVentura/neural-network-challenge-1.git
   ```
2. Open the folder corresponding to neural-network-challenge where you installed in using the repo clone above.

3. Open the file student_loans_with_deep_learning.ipynb

4. Make the modifications you desired. Run cell by cell or run the entire Jupyter notebook.
