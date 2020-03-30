
# Ocean Luxury Hotel Software
 A python application running TKinter that is meant to serve a hotel and their services.

## Requirements

 - Python 3

 - [Bcrypt](https://pypi.org/project/bcrypt/)
`pip install bcrypt`
 - [mysql-connector-python](https://pypi.org/project/mysql-connector-python/)
 `pip install mysql-connector-python`

## Screenshots
### Customer
#### Main Page
![alt text](https://i.imgur.com/rWa00Fh.png "Customer Main Page")
#### Purchasing a Snack
![alt text](https://i.imgur.com/nBYRX9u.png "Customer Purchasing a Snack")
#### Booking a Suite
![alt text](https://i.imgur.com/1I5Oj2K.png "Customer Booking a Suite")
### Employee
#### Checking in a Guest
![alt text](https://i.imgur.com/tT6Md15.png "Employee Checking In a Guest")
#### Viewing a Guest's Purchase History
![alt text](https://i.imgur.com/tvF5qBH.png "Employee Viewing Purchase Log")

## Running the Program
Just run main.py and the program should start up (Asumming python installed is python3)

`python main.py`

## Test Accounts
Below are acccount used to test both versions of the UI.



 User Type | Username | Password  |
-----------|----------|-----------|
  Front Desk | admin | admin |
 Guest | abcd | 1234 |


## Technical Problems
- .encode /.decode is varying on machine. Change that line in verify_login() in DatabaseFunctions.py if you run into that problem
