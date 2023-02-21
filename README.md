# Spark

### By Philip Kendall

#### This project utilizes PySpark to read a CSV file, turn it into PySpark DataFrame, transform it in various ways, and then write the final product into a parquet file. 
## Technologies Used

* GIT
* GCP
* Python 3.7
* PySpark
* JupyterNotebooks


## Description
First a CSV file called coffee.csv is read and turned into a PySpark dataframe. Then numerous columns are added based on different aggregate funcitons, filter conditions, and basic data manipulaiton. PySpark is then used to showcase different aggregate values of certain columns within the dataset. Finally, the PySpark dataframe is then written into a parquet file and stored in the data directory.

## Setup/Installation Requirements

* Fork over the the repository to your own Github account.
* Clone your Github repo down to your local machine and into the directory you would like this project to be stored.
* Create a virtual environment:
  ```
  python3.7 -m venv venv
  ```

* Navigate and set the Python Interperator and Kernel within your IDE to venv/bin/python.   

* Install the requirements.txt file:
  ```
  pip install -r requirements.txt
  ```
* Create a data directory and navigate into it:
  ```
  mkdir data
  cd data
  ```
* Execute the following command to recieve a copy of the coffee.csv file from GCP:
  ```
  gsutil -m cp gs://data.datastack.academy/coffee_price/coffee.csv
  ```
* Afterwards, navigate to the main.ipynb file and the project should be able to run.
## Known Bugs

N/A

## License

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The below copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) 2023 Philip Kendall