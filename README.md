# Analyzing-Aadhar-Cards-Data-Using-Apache-Pig
Analyzing Aadhar Cards Data using Apache Pig - and Find out the total number of cards approved by States, Find out the total number of cards rejected by states, Find out the total number of cards approved by cities, and Find out the total number of cards rejected by cities.
# Problem statement:
1. Find out the total number of cards approved by States.
2. Find out the total number of cards rejected by states.
3. Find out the total number of cards approved by cities.
4. Find out the total number of cards rejected by cities.

# Dataset Link
https://goo.gl/DbuFKb

# Data Set Description:
The data set consists of the following fields.

State: This field consists of the state names from all over India
City: This field consists of city names in all states
Approved: This fields consists of the total count of approved cards in numbers
Rejected: This field consists of the total count of rejected cards in numbers

# Codes and Explanation:
First we need to create a directory in HDFS. Creating a directory called pig in hdfs.

# Usecase1:
In this use case we are finding the total number of cards approved by States.

# Explanation for usecase1:
Load Aadhar details
group them by states
summing up the values of cards approved by each state
Finally storing the output into HDFS.

# OutPut Usecase1:
Below is the sample output screen for usecase1

# Usecase2:
In this use case we are finding total number of cards rejected by each states.

# Explanation for usecase2:
Load Aadhar details
group them by states
summing up the values of cards rejected by each state
Finally storing the output into HDFS.

# Usecase2 Output:

# Usecase3:
In this use case we are finding the total number of cards approved by cities.

# Explanation for usecase3:
Load Aadhar details
group them by states
summing up the values of cards approved by cities
Finally storing the output into HDFS.

# Usecase3 Output:

# Usecase 4:
In this use case we are finding the total number of cards rejected by cities.

# Explanation for usecase4:
Load Aadhar details
Group them by states
Summing up the values of cards rejected by cities
Finally storing the output into HDFS.

# Usecase4 Output:
