# ECE444-F2022-Lab6

## Unit test function in project
https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-6-lambda/blob/91db74dc28f5c7941adb63a7d25bba4788153f2e/Education_Pathways/tests/test_app.py#L20


## Pros and cons of TDD

### Pros
- TDD ensures that the application can be tested with high-quality automated tests. Since the tests are written before the application code, the developer doesn't need to rush to finish creating test cases before a tight project deadline. In addition, the tests will be generated directly against the requirements and architecture design, which eliminates the potential bias of creating test cases to confirm that the code is working.
- TDD focuses on QA automation, which can reduce the amount of  manual effort required to test the applicaiton both in the current release and in future regression testings.
- Since TDD usually tests application on the modular level, it is good at identifying issues at the early stage of development, making triaging and debugging much easier.

### Cons
- It takes time and effort to design and development TDD test cases, which might make it not feasible to teams with limited development resources.
- The maintanence of the test suite is also time consuming. For example, if there is a major refactoring of code, a lot of existing test cases in the test suite need to be rewritten as well.
- It requires good communication between the team developing the test cases and the team developing the software, if they are not the same team. If there is a lack of good mechanism for the teams to cooperate, a lot of time could be wasted on communiction.
- TDD could make the development process less agile. In fast-paced development teams, requirements could change quickly. Having these pre-defined tests makes it harder for the team to respond to requirement changes.
