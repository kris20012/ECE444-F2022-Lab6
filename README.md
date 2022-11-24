# ECE444-F2022-Lab6

Krishanth Suthaharan

Note: This repo follows instructions from https://github.com/mjhea0/flaskr-tdd

##### Application is deployed to: 
https://python-testing-app-lab6.herokuapp.com/

##### Test cases for group project:
https://github.com/ECE444-2022Fall/curriculus/blob/34664ff0202b048d0070c171fd36d5d4d3e0b223/Education_Pathways/tests/test_app.py#L135-L173

## Pros and Cons of Test Driven Development
### Advantages
There are many benefits to test driven development (TDD). By writing tests first based on feature requests/specifications, the testing process will not be rushed and a higher quality application is implemented. It can also help bring team members to be on the same page in terms of what is expected of their application to do and helps with the agile methodology because sprints often have a limited timeframe and being able to write code that’s only needed to make the test pass and refactor it is more efficient and easier. In addition, it forces modularity in the code, otherwise they would be hard to test. This shows that the code will be easier to maintain as a developer will have a better understanding of how each module interfaces with one another. It also offers less debugging in the long run. During deployment, it will also give developers more confidence since they would understand the application is passing their test cases.

### Disadvantages
Although there are several benefits of adopting TDD in development, there are several drawbacks. The first drawback is slow start up time for development. The tests may be hard to write up for example integration testing since the dependencies may not be completely clear at that point and it may also be challenging to enforce testing to the whole team. If all the team members don’t abide, it will be difficult for the TDD to influence the design and planning of code. Some additional time must be allocated to learn the process when doing it for the first time on your own and requires lots of dedication or practice and it’s hard to start working with this methodology if a coder has been finding their own effective implementation techniques. Lastly, the test suite must be maintained especially when written from the start and the requirements change, it may require refactoring the test cases early on.
