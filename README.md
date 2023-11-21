# Encapsulation

# People
Create a class Person, which should have public properties with private setters for:
 FirstName: string
 LastName: string
 Age: int
 ToString(): string - override

# Salary
Create objects of the class Person. Read their name, age, and salary from the console. Read the percentage of the 
bonus to every Person's salary. People younger than 30 get half the increase. Expand Person from the previous 
task.
New properties and methods:
 Salary: decimal
 IncreaseSalary(decimal percentage)

# Validation
Expand Person with proper validation for every field:
 Name must be at least 3 symbols
 Age must not be zero or negative
 Salary can't be less than 460 (decimal)
If some of the properties are NOT valid throw ArgumentExeption with the following messages:
 "Age cannot be zero or a negative integer!"
 "First name cannot contain fewer than 3 symbols!"
 "Last name cannot contain fewer than 3 symbols!"
 "Salary cannot be less than 650 leva!"

# Team
Create a Team class. Add to this team all of the people you have received. Those who are younger than 40 go to the 
first team, others go to the reserve team. At the end print the sizes of the first and the reserved team.
The class should have private fields for:
 name: string
 firstTeam: List<Person>
 reserveTeam: List<Person>
The class should have constructors:
 Team(string name)
The class should also have public properties for:
 FirstTeam: List<Person> (read-only!)
 ReserveTeam: List<Person> (read-only!)
And a method for adding players:
 AddPlayer(Person person): void
