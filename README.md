# Classes Review

## Due: Tue 9/5 at 11:59 PM

- Create a program called `Student.java`
- The Student class should have the following data members
  - name
  - age
  - ID number
  - grade
  - gpa
- The Student class should have the following constructors
  - default
  - parameterized with all five parameters
- The Student class should have getter and setter methods for all five data members
- The Student class should have a toString method that returns the name and ID number of the student separated by a comma and a space
- The Student class should have the following methods
  - an isHonorRoll() method which returns true if the GPA is greater than or equal to 3.0
  - an isUpperClassmen() method which returns true if the student is a junior or a senior
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
- Create a program called `StudentTester.java`
- Create a Student object using the default constructor
- Prompt the user for the following values and store them in variables:
  - name
  - age
  - ID number
  - grade
  - gpa
- Use the setter methods to assign those values to the Student object
- Prompt the user again for the following values and store them in separate variables from the last time you read values in:
  - name
  - age
  - ID number
  - grade
  - gpa
- Use those values to create another Student object using the parameterized constructor
- For each Student:
  - Print the result of the toString method
  - Print the result of the isHonorRoll method
  - Print the result of the isUpperClassman method

***Example Input:***\
John Deere\
18\
100010412\
12\
4.0\
Will Smith\
15\
100012345\
10\
2.8\
***Example Output:***\
John Deere, 100010412\
true\
true\
Will Smith, 100012345\
false\
false
