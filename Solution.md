# Code Explain
## 1. generate_password()
### Parameters: length, complexity level
### Expalanation:
Given complexity we are checking the levels to ensure that the password created has been using the constraints of that level using if-else cases and random function.

## 2. check_password_level()
### Parameters: password
### Explanation:
A hashmap is used to check the characters of password to ensure to which level does they belong to and then the largest level recorded in the hashmap is returned. 
This code also takes care of the exception conditions by checking the password length and returning the actual complexity the password.

## 3. add_to_map()
### Parameters: Complexity Level, Values, Map Reference 
### Explanation: 
This extra function created will add the values in the map according to its complexity level.

## 4. create_user()
### Parameters: database_path
### Explanation: 
Establishing connection with the database using request and storing the information retrieved from Json api given into database using sqlite datapath.
SQL commands executed using cursor. 




The code includes other scripts to check and validate the above functions. Assertion is also used to check working of generate_password and check_password_level.
