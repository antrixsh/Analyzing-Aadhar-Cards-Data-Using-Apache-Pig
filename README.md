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

1.State: This field consists of the state names from all over India
2.City: This field consists of city names in all states
3.Approved: This fields consists of the total count of approved cards in numbers
4.Rejected: This field consists of the total count of rejected cards in numbers

# Codes and Explanation:
First we need to create a directory in HDFS. Creating a directory called pig in hdfs.
![capture](https://user-images.githubusercontent.com/26787806/51824122-6eabb200-2307-11e9-8306-10672bd896a0.PNG)

# Usecase1:
In this use case we are finding the total number of cards approved by States.
![capture1](https://user-images.githubusercontent.com/26787806/51827032-73c02f80-230e-11e9-94ae-8f77d74760a6.PNG)
# Explanation for usecase1:
1.Load Aadhar details
2.group them by states
3.summing up the values of cards approved by each state
4.Finally storing the output into HDFS.

# OutPut Usecase1:
Below is the sample output screen for usecase1

![capture11](https://user-images.githubusercontent.com/26787806/51827067-8aff1d00-230e-11e9-8dd0-7ccf965be9c1.PNG)

# Usecase2:
In this use case we are finding total number of cards rejected by each states.
![capture2](https://user-images.githubusercontent.com/26787806/51828388-7ec88f00-2311-11e9-9119-5a783b6fc8a4.PNG)
# Explanation for usecase2:
1.Load Aadhar details
2.group them by states
3.summing up the values of cards rejected by each state
4.Finally storing the output into HDFS.

# Usecase2 Output:

![capture12](https://user-images.githubusercontent.com/26787806/51828417-90119b80-2311-11e9-9273-f25fb411fcda.PNG)

# Usecase3:
In this use case we are finding the total number of cards approved by cities.
![capture21](https://user-images.githubusercontent.com/26787806/51828460-a881b600-2311-11e9-8cda-6fe56ab622ee.PNG)
# Explanation for usecase3:
1.Load Aadhar details
2.group them by states
3.summing up the values of cards approved by cities
4.Finally storing the output into HDFS.

# Usecase3 Output:
![capture22](https://user-images.githubusercontent.com/26787806/51828491-b3d4e180-2311-11e9-9cb6-8bb646a2915e.PNG)

# Usecase 4:
In this use case we are finding the total number of cards rejected by cities.
![capture31](https://user-images.githubusercontent.com/26787806/51828526-c3ecc100-2311-11e9-95c8-1adfe1f32779.PNG)
# Explanation for usecase4:
1.Load Aadhar details
2.Group them by states
3.Summing up the values of cards rejected by cities
4.Finally storing the output into HDFS.

# Usecase4 Output:
![capture32](https://user-images.githubusercontent.com/26787806/51828553-d2d37380-2311-11e9-92a4-497a11ce3cd6.PNG)

