Test Case 01
Test Case ID: TC_CALC_001
Test Description: Verify addition of two positive integers
Preconditions: Calculator is open and functional
Test Steps:
Enter 10
Press +
Enter 5
Press =
Expected Result: Result displayed as 15

Test Case 02
Test Case ID: TC_CALC_002
Test Description: Verify subtraction with negative result
Preconditions: Calculator is open
Test Steps:
Enter 8
Press -
Enter 12
Press =
Expected Result: Result displayed as -4

Test Case 03
Test Case ID: TC_CALC_003
Test Description: Verify multiplication of two decimal numbers
Preconditions: Calculator is open
Test Steps:
Enter 2.5
Press *
Enter 4.2
Press =
Expected Result: Result displayed as 10.5

Test Case 04
Test Case ID: TC_CALC_004
Test Description: Verify division of a number by a non-zero number
Preconditions: Calculator is open
Test Steps:
Enter 20
Press /
Enter 4
Press =
Expected Result: Result displayed as 5

Test Case 05
Test Case ID: TC_CALC_005
Test Description: Verify division by zero (invalid input)
Preconditions: Calculator is open
Test Steps:
Enter 9
Press /
Enter 0
Press =
Expected Result: Error message displayed: "Cannot divide by zero"

Test Case 06
Test Case ID: TC_CALC_006
Test Description: Verify BODMAS rule execution
Preconditions: Calculator is open
Test Steps:
Enter 5 + 2 * 3
Press =
Expected Result: Result displayed as 11 (Multiplication evaluated first)

Test Case 07
Test Case ID: TC_CALC_007
Test Description: Verify input of non-numeric characters
Preconditions: Calculator is open
Test Steps:
Enter 5 + a
Press =
Expected Result: Error message displayed: "Invalid input"

Test Case 08
Test Case ID: TC_CALC_008
Test Description: Verify addition of negative numbers
Preconditions: Calculator is open
Test Steps:
Enter -7
Press +
Enter -3
Press =
Expected Result: Result displayed as -10
