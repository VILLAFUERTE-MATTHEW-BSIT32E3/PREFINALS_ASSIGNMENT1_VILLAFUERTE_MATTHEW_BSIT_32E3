# PREFINALS_ASSIGNMENT1_VILLAFUERTE_MATTHEW_BSIT_32E3

Onion Architecture: (Yes/No) 
 
Have you heard of the Onion Architecture principle in software design?
--YES
 
 
MVC Pattern: (Yes/No) 
 
Are you familiar with the Model-View-Controller (MVC) pattern for building web applications?
--YES
 
 
Web API: (Yes/No) 
 
Do you understand the concept of building RESTful APIs using ASP.NET Core Web API?
 
--YES
 

Application & Bottlenecks:
Onion Architecture:
 
 
Benefits: (1-3 keywords)
 
 
Briefly list some key benefits of using Onion Architecture in .NET Core projects. (e.g., separation of concerns, testability)
--Separation of concerns
--Testability
--Maintainability
  
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
 Have you encountered any challenges with Onion Architecture in your projects? If so, briefly describe the bottleneck(s). (e.g., Increased complexity for simple projects, difficulty finding developers familiar with the pattern)
--Yes. Challenges include increased complexity for simple projects and difficulty finding developers familiar with the pattern. The layered approach can also result in higher initial setup time and effort.
 
 
 

MVC:
 
 
Components: (1-3 keywords each)
 
 
Briefly describe the roles of the Model, View, and Controller in the MVC pattern.
--Model: Data and business logic management
--View: Data presentation and user interaction
--Controller: User input handling and model-view coordination
 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
Have you encountered any challenges with tight coupling between Model and Controller in MVC projects? If so, briefly describe the issue(s). (e.g., Difficulty in unit testing controllers, logic changes rippling through the application)
--Difficulty in testing controllers
--A lot of logic changes reducing flexibility.
--Reduced reusability
 
Web API:
 
 
Differences from MVC: (Yes/No and Briefly Explain)
Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
--Yes. Traditional MVC combines data processing with rendering UI, while Web APIs focus solely on data exchange via HTTP endpoints.
 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
Have you encountered any performance challenges with traditional MVC applications compared to Web APIs? If so, briefly describe the scenario(s). (e.g., Frequent page refreshes causing performance overhead, complex data exchange requiring a more lightweight approach)
--Yes. Traditional MVC can suffer from performance overhead due to frequent page refreshes and is less efficient for complex data exchange compared to Web APIs.
