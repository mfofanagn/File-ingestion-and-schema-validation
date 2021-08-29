# File-ingestion-and-schema-validation

Take two  csv/text file . 
  california_housing_train.csv 
  used_cars_data.csv

Read the file ( Present approach of reading the file )


Compare different methods of file reading eg: Dask, vs ,  pandas and present  findings in term of computational efficiency
  We noticed that Dask in more computational efficient than pandas, moreover when the input file is too big (case for used_cars_data.csv) pandas may freezed
  

Create a YAML file and write the column name in YAML file. --define separator of read and write file, column name in YAML

Perform basic validation on data columns : eg: remove special character , white spaces from the col name

Validate number of columns and column name of ingested file with YAML.

Write the file in pipe separated text file (|) in gz format.

Create a summary of the file:

Total number of rows,

total number of columns

file size
