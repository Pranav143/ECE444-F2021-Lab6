# ECE444-F2021-Lab6

### TDD Discussion
#### Pros
Test driven development forces the developer to have a thorough understanding of each piece of code they write, before they write it. This prompts establishing requirements clearly ahead of time, and gives foresight and reduces the chances of forgetting import aspects of the code later on. Moreover, by writing all these tests, it also forces breaking down code logic into smaller modular chunks. This makes tweaking and refactoring the code later on easier. And of course, the most obvious benefit is the fact that every part of the application is tested, and the app coverage is really high. This is good as a safeguard against regressions. If someone makes code changes, the developers can be sure that the desired behaviour is not lost since the tests will catch a possible regression. 

#### Cons
Since every small unit of code is tested for, there is a heavy burden of test maintenance. Every update to applications or tweaks requires also changing and updating the tests. This is not bad in terms of code quality, but rather for development speed. Also, writing so many tests might lock the developer into a certain path and deny flexibility if they want to change a large portion of the application. It can also be difficult to write tests ahead of time when you may not have clear understandings of what is needed for the application, thus slowing down the beginning process of the development cycle. This is also an ongoing commitment. You cannot have team members stop doing TDD or else the whole point is lost. 
