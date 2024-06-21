The folder contains code for tasks pertaining to ECG and HR, RR data.

The dependency for the file is python 3.10.12 and the code has been run on Linux. For Mac, the code should also work fine. There might be issues with Windows operating system based on the file structures.

A seperate virtual environment has been created for this project. Venv has been used instead of conda since it runs easily on euler and leads to lower number of files.

Setup a new python environment using:
```
python -m venv ./venv
source venv/bin/activate
```
Download all the libraries using:
```
pip install -r requirements.txt
```

The data should be kept in the folder "ECG_data". In the root directory, downloading the zip file and extracting it should be enough.

The code is self-contained in the analysis.ipynb notebook. A notebook has been used to provide the outputs without running the files as well as provide an interactive way to explore the data and code.