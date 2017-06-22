# Final Exam

## Terms
1. Duration: **3 hours**.
1. **Two problems** to solve.
1. Each problem brings you upto 100 points.
1. Submit all your work as **.zip** file (remove **obj** and **bin** folders from each project in your solution).
1. Solutions that doesn't compile, will lead to **failed exam**.
1. Similar projects (more than 80%) will lead to **failed exam** regardless of the original author.
1. Provide a `README.md` if your solution needs additional information (used packages, configs etc.).
1. Send your solution to the course trainer for evaluation.
    * Name your submission in the format `[YourName]-[Course]-[ExamName]-[Date]` 
    * For example: `EvgeniKostadinov-SBTechQaAutomation-MidTerm-25042017.zip`

## Evaluation criteria
| Automation                  | Max Score |  Comments                                                                        |
| ------------------------ | --------- | ------------------------------------------------------------------------------------| 
|  Completness | 150 pts    | All test cases are implemented, code submitted                                     | 
|  Quality     | 50 pts    | Good code quality, code is modular, used design patterns and principles             |

## Tips
1. Follow all good practices learned so far, like [High quality code](https://github.com/ekostadinov/edojoit-autot-csharp-sbt/tree/master/Track-I/09.High-quality-code). Not formatted code, poor naming, useless comments .etc will **lead to lower grade**.
1. Use what you've learned from doing your homeworks with [Selectors](https://github.com/ekostadinov/edojoit-autot-csharp-sbt/tree/master/Track-II/02.DocumentObjectModel.Locators-basics), [Test flow control](https://github.com/ekostadinov/edojoit-autot-csharp-sbt/tree/master/Track-II/04.Test-flow-control-Waits) and [Design patterns](https://github.com/ekostadinov/edojoit-autot-csharp-sbt/tree/master/Track-II/05.Design-principles-and-patterns).


## Exam Grades
| Student             | Points |  Comments                                                                              |
| ------------------- | ------ | -------------------------------------------------------------------------------------- | 
| Dimitar Batinov     |  10    | partial first problem submitted (no real tests); commented code;                      |
| Emil Georgiev       |  60    | only second problem submitted; good naming; single low level NUnit test;              |
| Ivan Angelov        |  60    | only first problem submitted; good naming; only low level NUnit tests; not fully correct use of `using`;                   |
| Kosta Grudov        |  60   | both problems submitted; random test data is generated; wrong email format (missing `@`) in second one; redundant comments; absolute paths in selectors; single assert (miss-placed) in first problem;              |
| Nikolay Kostov      |  60   | only first problem submitted; good naming; only low level NUnit tests;                  |
| Lyubomir Atanassov  |  0   | `.sln` file not submitted; `ScreenShotRemoteWebDriver` (at `http://hub-cloud.browserstack.com/wd/hub/` with no user/key pair) and `Thread.Sleep` is used; Totally unrelated to the exam tests (create github repo; `Test_Google_HelloWorld`) |
| Vidko Videv         |  40   | solution can't be build (uninitialized local variables used); good naming; control flow used as exception handling; only low level NUnit tests; hardcoded selectors; little emphasis to make code generic;            |
| Tsvetelina Ruseva   |   90  | first problem - single Test method, no Assertion; second problem - dynamic test data is used; redundant comments; only low level NUnit tests; |
| Tzvyatko Kolev      |  30   | only first problem submitted; poor naming; redundant comments; single assert (miss-placed); |
| Vladislav Georgiev  |  30   | only first problem submitted; 3 `namespace`s in single file; `NavigatinThruUrlsShouldWork` is not a real test (no code in ` [TestMethod]`, no Assertion); redundant comments; |
| Zhivko Kostov       |  60   |   only first problem submitted; poor xpath; |
| Victor Stanchin     |  0   | Midterm exam submitted.              |
| Nikolay Stamenov    |  90   | both problems submitted; UI tests from the first one don't follow the exam terms; left comments (plus `IJavaScriptExecutor` use);  `ITakesScreenshot` and exceptions handling  implemented; redundant duplicated `Assert` in second problem; |
| Tsvetelina Banchevska | 40  | partial first problem submitted (2/3 tests); good naming; redundant comments;          |
| Milen Zakov           | 40  | partial first problem submitted (2/3 tests); absolute paths in selectors; Unreferenced `internal class WebDriverWait`;  |
| Miroslav Kazakov      | 60   |  only first problem submitted; good naming; only low level NUnit tests; little emphasis to make code generic;  |
