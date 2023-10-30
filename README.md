# ECE444-F2023-Lab5 - Himanish Jindal
This repo is a clone of https://github.com/mjhea0/flaskr-tdd

# Activity 2
I've created unit test functions for our SQLAlchemy database in the following [file](https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/pull/16/files#diff-142d762c5d7485f2807b608479fd8a10bf78a58f598d85e4d2ada795c7d230c8).

PR for this change: [#16](https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/pull/16)


# Activity 3:
Pros of TDD:
- The main benefit of testing in general is to reveal bugs, assess quality, clarify the specification, and for verification purposes. 
- It forces developers to automate our testing process from the beginning of the code development process. This allows for continuous testing as developers continue coding. This would also allow developers to setup the GitHub CI/CD Pipeline to test their code as well and ensure that code doesn't break with new commits/changes.
- Writing tests before development also helps to unify the team on how the implementation will work. As the developer designs the test, they need to think of the final outcome of their code and ensure that all team members agree with the expected result of the feature implementation. This helps to prevent any unnecessary code deletions/revisions in the future because the team was able to finalize their decision on how the feature will function.
- At the time of deployment, using the TDD methodology helps to give a higher degree of confidence. The developer knows that they coded the functionality while constantly checking to make sure they pass the unit tests. This allows them a level of confidence that their code passes the unit tests and does function as intended.
- The TDD Methodology also works very well in tandem with the Agile methodology as they are both very iterative processes and emphasize small changes through a cyclic process. This refactoring process allows for small changes over time allowing for developers to write unit tests for small code changes in one iterative cycle.

Cons of TDD:
- TDD can sometimes slow down the development process as the developer has to constantly write tests to verify their code functions as intended. As the developer needs to write tests before writing the code, this can be difficult if the specifications for the code are unclear. If the code is complex or requires more analysis or the developer is unsure of the end product, it can be hard to write unit tests before writing any code.
- Writing a lot of unit tests could also result in a huge test suite that takes hours/days to complete on a large codebase. This could be the result of having tests for every single function which may be unnecessary and could be replaced with an Integration test
