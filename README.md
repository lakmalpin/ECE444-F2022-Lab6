**Lab 6**


Lakmal Pinnaduwage - This lab is based on: https://github.com/mjhea0/flaskr-tdd

**Group Project Test Cases**

https://github.com/ECE444-2022Fall/project-1-web-application-design-education-pathways-group-17-mergers/blob/5a424df2862b3090fac556f6dcfc57c98b18febd/Education_Pathways/tests/test_app.py#L162-L195

**Pros and Cons of TDD**

TDD is a style of agile software development where tests are written before any code is implemented, and as you add code, you use the tests to verify that the new code is functional.

Pros: 
* Written code is often directly meeting requirements because it is written to pass the test. This results in less excess code and no wasted efforts developing things that aren't part of the main requirements.
* Code is naturally formatted in a way that is easy to test.
* Code becomes more extensible as it can be easily refactored and reorganized with little chance of the code breaking.
* TDD encourages other coding practices like OOP which helps build a strong and cohesive code base.
* Ensures that developers really understand the code they produce and prevents unnoticed bugs from appearing
* Adds tests to a code base naturally, saving a lot of time for things like regression cycles.
* When adding features, TDD ensures that new code changes don't break anything else.

Cons: 
* The quality of code developed is heavily dependent on the strength of the tests written, so bad unit test designs can result in weak and incomplete code.
* This coding technique must be applied to a new code base as it is hard to integrate into an existing code base
* It may be hard to write tests especially initially as it is more abstract. Therefore, you must have a strong understanding of TDD in order to develop good code out of it.
* You must always manage tests because they are continuously added
* It can be a time-consuming process, especially early on when teams are learning how to effectively develop tests.
* Harder to use in an Agile setting, when you want to push out features as fast as possible, and tests take additional time but do not add anything for the user.   