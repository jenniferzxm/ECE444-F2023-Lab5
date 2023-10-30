# ECE444-F2023-Lab5

replicate of https://github.com/mjhea0/flaskr-tdd/tree/main

test case(s) to project: test_search_event_keywords function
link: https://github.com/ECE444-2023Fall/project-1-web-application-design-group4-3d3g/blob/main/tests/test_app.py#L66-L83


What are the pros and cons of TDD?
The pros of test-driven development are ensuring the functionality of code under a rapid development environment. It will also have a more gradual step progression (but has many steps) which brings the main benefit of breaking down into subproblems to tackle, making it easier to integrate and test. From the rapid changes, the scope of each problem is reduced so it helps the developer to pick out the error. Moreover, it will help the developer write a less error-prone implementation by consciously thinking about the possible corner cases (and hopefully incorporating the resolution to them). Then, the overall quality in terms of the functionality will also increase. Another aspect of the pros is also easier for another developer to pick up on the work since it is “well-documented” in the sense that the stages of progression are very clear and easy to follow. 

The cons of test-driven development (TDD) are the “rigidness” and high maintenance of the overall development framework. These two are very heavily correlated since if there is a major system update, then it is very likely that all of the test cases need to be updated to reflect the change. It also makes it very costly to maintain especially at the beginning (where major changes happen more often). Moreover, if there is a mismatch between the test case and code functionality (i.e. test cases don’t cover all the functionality), it has the potential to deploy malfunctioning code. 

