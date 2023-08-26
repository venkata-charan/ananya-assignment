# Assignment 1: JSON-to-CSV Conversion Utility


## Problem Statement:
Your task is to design and implement a python utility that accomplishes JSON-to-CSV Conversion.

### JSON-to-CSV Conversion:
The utility should be capable of reading data from multiple JSON files, each containing a list of records in JSON format.
It should consolidate the data from all JSON files into a single CSV file.
Apply SOLID principles to design the utility, ensuring modularity and separation of concerns.

#### Logging:
Incorporate proper logging to track essential events, such as the start and completion of data conversion.
Log any errors that occur during file processing or data conversion.

#### Sample Data:
For testing purposes, consider the following sample data:

##### JSON Files in Folder Structure:
```
input_data/
├── folder1/
│   ├── data1.json
│   └── data2.json
├── folder2/
│   ├── data3.json
└── data4.json
└── other_file.txt
```
##### Example data1.json:
Multiple independent json records in a file

```
    {"Name": "Alice", "Age": 28, "Salary": 50000}
    {"Name": "Bob", "Age": 35, "Salary": 60000}
```

##### Example CSV File Output:
After processing the sample data, your utility should create a CSV file with consolidated data like:

```
Name,Age,Salary
Alice,28,50000
Bob,35,60000
```

###### Hint:
The input folder for your utility should support a nested folder structure containing JSON files. The utility should traverse the directory and its subdirectories to consolidate all JSON data into a single CSV file.
Submission:

#### Estimated Time to complete:
5 Days

#### Candidates should follow these steps for submission:
* Create a PR in this repo - https://github.com/venkata-charan/ananya-assignment
* Commit your code, test cases, documentation, and any other necessary files to the repository.
* Include clear instructions on how to run the utility, execute tests, and interpret the logs in the repository's README.

##### Evaluation Criteria:
Below principles will be used to evalaute your assessment :

* Design and implement a clean, modular, and SOLID-compliant codebase for JSON-to-CSV conversion.
* Apply the DRY principle effectively to enhance code maintainability.
* Devise thorough test cases that encompass various scenarios and edge cases.
* Integrate logging to facilitate proper event tracking and error handling.
