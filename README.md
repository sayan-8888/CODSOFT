AUTHOR - SAYAN CHAKRABORTY.
TASK - 1  NUMBER GAME
Description
A Java console application where players guess a randomly generated number within a range, with scoring based on the number of attempts.
Explanation
This code implements a Number Guessing Game where players have up to five attempts per round to guess a number between 1 and 100. 
The player's score increases based on the number of attempts remaining when they guess correctly. 
After each round, the player can choose to play again, and their final score is displayed when they decide to stop.

EXAMPLE CODE INPUT AND OUTPUT:-
Round 1: Guess the number between 1 and 100
Attempt 1 - Enter your guess: 23
Too low! Try again.
Attempt 2 - Enter your guess: 78
Too high! Try again.
Attempt 3 - Enter your guess: 92
Too high! Try again.
Attempt 4 - Enter your guess: 56
Too low! Try again.
Attempt 5 - Enter your guess: 99
Too high! Try again.
Sorry, you've used all your attempts. The correct number was: 75
Do you want to play again? (yes/no): no
Game Over! Your final score is: 0


TASK - 2 STUDENT GRADE CALCULATOR
Description
A Java console application that calculates and displays a student's total marks, average percentage, and grade based on input marks for each subject.
Explanation
This code prompts the user to enter the number of subjects and their respective marks, calculates the total marks and average percentage, and then determines the grade based on predefined percentage thresholds. The results, including the total marks, average percentage, and corresponding grade, are then displayed to the user.

EXAMPLE CODE INPUT AND OUTPUT:-

Enter the number of subjects: 5
Enter marks obtained in subject 1 (out of 100): 98
Enter marks obtained in subject 2 (out of 100): 95
Enter marks obtained in subject 3 (out of 100): 93
Enter marks obtained in subject 4 (out of 100): 92
Enter marks obtained in subject 5 (out of 100): 98
Total Marks Obtained: 476
Average Percentage: 95.2%
Grade: A



TASK - 3 ATM INTERFACE
Description
A Java application simulating an ATM interface allowing users to deposit, withdraw, check balance, and exit using a bank account.
Explanation
This code defines an ATM class and a BankAccount class to simulate basic ATM functionality. The BankAccount class manages the balance and performs transactions, while the ATM class provides a user interface to interact with the bank account, allowing deposits, withdrawals, balance checks, and exit options. The ATMInterface class initializes the system and starts the ATM interface with a sample balance.

EXAMPLE CODE INPUT AND OUTPUT:-

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance        
4. Exit
Choose an option (1-4): 3
Your current balance is: Rs. 1000.0

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option (1-4): 1
Enter the amount to deposit: 200
Successfully deposited: Rs. 200.0

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option (1-4): 3
Your current balance is: Rs. 1200.0

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option (1-4): 2
Enter the amount to withdraw: 400
Successfully withdrew: Rs. 400.0

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option (1-4): 3
Your current balance is: Rs. 800.0

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Exit
Choose an option (1-4): 4
Thank you for using the ATM. Goodbye!





TASK - 4 QUIZ APPLICATION WITH TIMER
Description
A Java quiz application that presents multiple-choice questions with a timer for each question, tracks the score, and displays the results at the end.
Explanation
This code implements a quiz application where users answer multiple-choice questions within a 15-second time limit per question. It uses a Timer to enforce the time limit and tracks the user's score based on correct answers. The QuizApplication class initializes the quiz with predefined questions, starts the quiz, and displays the final score at the end.

EXAMPLE CODE INPUT AND OUTPUT:-
Question 1: What is the capital of France?
1. Berlin
2. Paris
3. Madrid
4. Rome
Enter your answer (1-4): 2
Correct!
Question 2: Which planet is known as the Red Planet?
1. Earth
2. Mars
3. Jupiter
4. Saturn
Enter your answer (1-4): 2
Correct!
Question 3: Who wrote 'Hamlet'?
1. Charles Dickens
2. Leo Tolstoy
3. William Shakespeare
4. Mark Twain
Enter your answer (1-4): 3
Correct!
Question 4: What is the largest ocean on Earth?
1. Atlantic Ocean
2. Indian Ocean
3. Southern Ocean
4. Pacific Ocean
Enter your answer (1-4): 4
Correct!
Question 5: Which element has the chemical symbol 'O'?
1. Oxygen
2. Gold
3. Osmium
4. Oganesson
Enter your answer (1-4): 1
Correct!

Quiz Over!
Your final score is: 5 out of 5



TASK - 5 STUDENT COURSE REGISTRATION SYSTEM
Description
A Java Student Course Registration System that allows students to register for, drop, and view courses, with functionalities for managing course and student data.
Explanation
This code provides a system for managing student course registrations. It includes features for displaying available courses, registering and dropping courses, and viewing a student's registered courses. The system uses HashMap to store course and student information and offers a command-line interface for user interaction.

EXAMPLE CODE INPUT AND OUTPUT:-

--- Student Course Registration System ---
1. Display Available Courses 
2. Register for a Course     
3. Drop a Course
4. Display Registered Courses
5. Exit
Choose an option (1-5): 1    

Available Courses:
----------------------------------
Course Code: CS101
Title: Introduction to Computer Science
Description: Basic concepts of computer science.
Schedule: Mon/Wed 10:00-11:30 AM
Capacity: 30
Available Slots: 30
----------------------------------
Course Code: MATH101
Title: Calculus I
Description: Introduction to differential and integral calculus.
Schedule: Tue/Thu 09:00-10:30 AM
Capacity: 25
Available Slots: 25
----------------------------------
Course Code: ENG101
Title: English Literature
Description: Study of classic and modern literature.
Schedule: Mon/Wed 01:00-02:30 PM
Capacity: 20
Available Slots: 20

--- Student Course Registration System ---
1. Display Available Courses
2. Register for a Course
3. Drop a Course
4. Display Registered Courses
5. Exit
Choose an option (1-5): 2
Enter your Student ID: S003
Enter Course Code to register: ENG101
Successfully registered for English Literature

--- Student Course Registration System ---
1. Display Available Courses
2. Register for a Course
3. Drop a Course
4. Display Registered Courses
5. Exit
Choose an option (1-5): 4
Enter your Student ID: S003
Registered Courses for Sayan Chakraborty (ID: S003):
- English Literature (ENG101)

--- Student Course Registration System ---
1. Display Available Courses
2. Register for a Course
3. Drop a Course
4. Display Registered Courses
5. Exit
Choose an option (1-5): 5
Exiting the system. Goodbye!


