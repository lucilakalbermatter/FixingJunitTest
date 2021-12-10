# Exercise - Resolve Problems in JUnits

> **Background**

The **EmployeeManager** is an application that provides couple of important features to manage employee records.
- To initialize the employee list by loading the data from a JSON database
- To sort the employee records using an *EmployeeComparator* class that implements the *Comparator* interface
- To access the employee list

There are a couple of unit test classes implemented in the project. Each test class consists of multiple test cases. However, due to some missing pieces or programming mistakes, the test cases are not working as expected. 

You are expected to resolve those issues and make sure all test cases are executing and reporting green as per the goal defined alongside the test cases.

> **Pre-work**

- Import the project in Eclipse or the IDE or your choice.
- Ensure that the project has following artifacts
- ![alt File Structure](./files/files.JPG)
- Verify that the file "data/employees.json" has the following content.

```
[
	{"name":"Sham", "email":"sham2020@gmail.com"},  
    {"name":"Bob", "email":"bob32@gmail.com"},  
    {"name":"Jai", "email":"jai87@gmail.com"}  
]

```
- Run the Java class named "main.java.EmployeeManager" as a *Java application*. 
- Ensure it executes and displays following result in the system console.

```
[Sham, Bob, Jai]
[Bob, Jai, Sham]
```

- Run the Test class named "incorrect.TestEmpListSize" as *JUnit Test*.
- Ensure it executes and displays the following result.
- ![alt TestEmpListSize Has 4 errors](./files/err1.JPG)


- Run the Test class named "incorrect.TestEmpShuffle" as *JUnit Test*.
- Ensure it executes and displays the following result.
- ![alt TestEmpShuffle Has 2 fails](./files/err2.JPG)

 **Tasks**

You are expected to do the following:

 **Task # 1** - Fix the cause of error in "incorrect.TestEmpListSize" class.

> *Hint*  
> - Do not modify the implementation of test cases as all of them are correct. 
> - There is a missing function/JUnit life-cycle function. 


**Task # 2** - Fix the cause of failures in "cincorrect.TestEmpListSize" class.

> *Hint*  
> - The failing test cases have incorrect implementation. 
> - Match the implementation with the goal of the test case as described in the *Display Name*. 

 **Bonus : Task # 3** - Write a Test Suite to execute both of the above test classes together.

> *Hint*  
> - Ensure Task #1 and Task # 2 are implemented correctly. 



