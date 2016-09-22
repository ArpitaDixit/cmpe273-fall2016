**Running Test Script**

Run the commands
 ```sh
 pip install requests
 ```
 Run your program (Flask) and see to it that your server is running on localhost:5000
 
 Run the test script
 
 ```
 python assignment1_check.py --student_id <your_student_id> --assignment_name assignment1 --url http:\/\/localhost:5000 --first_name <Your_first_name> --last_name <your_last_name> --email_id <your_email_id>
 ```
 
 ex:
 ```
 python assignment1_check.py --student_id 010095345 --assignment_name assignment1 --url http:\/\/localhost:5000 --first_name Nagkumar --last_name Arkalgud --email_id nagkumar.arkalgud@sjsu.edu
 ```
 
 If your first name/last name has a space, please use a \ before the space. Ex.
 ```
 python assignment1_check.py --student_id 010095345 --assignment_name assignment1 --url http:\/\/localhost:5000 --first_name Long\ First\ Name --last_name Long\ Last\ Name --email_id nagkumar.arkalgud@sjsu.edu
 ```
 