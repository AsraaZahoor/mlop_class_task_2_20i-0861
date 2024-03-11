#--------mlop_class_task_2_20i-0861--------#

This repository contains the code for the MLOps class task-2, which involves creating a Python class for managing students in MLOps, writing test cases, and setting up GitHub Actions for automated testing.

#--------StudentsInMLOps Class--------#

The StudentsInMLOps class is designed to manage student enrollment and dropout in MLOps. It includes the following functions:

- `enrollStudents(num)`: Enroll a specified number of students.
- `dropStudents(num)`: Drop a specified number of students.
- `getTotalStrength()`: Get the total strength of enrolled students.
- `getClassName()`: Get the name of the class.

#--------Testing--------#

Test cases for the `StudentsInMLOps` class are written in the `test.py` file. The tests cover the functionality of enrollment, dropout, and class name retrieval.

#--------Workflow--------#

GitHub Actions workflow is set up to run on every push event to the `main` branch. The workflow includes steps for checking out the code, setting up the Python environment, installing dependencies, and executing the test cases using pytest.

#--------Usage--------#

To use this code, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Navigate to the project directory: `cd your-repo`
3. Run the tests locally: `make test`

Below is the workflow that passed all tests:

![image](https://github.com/AsraaZahoor/mlop_class_task_2_20i-0861/assets/125173520/f380fd74-2482-4ad9-b2ef-b3b408e75263)

![image](https://github.com/AsraaZahoor/mlop_class_task_2_20i-0861/assets/125173520/b9bce124-c07d-4085-8c19-54953cd0b7af)



