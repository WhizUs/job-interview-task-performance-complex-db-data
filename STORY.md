# The Story

## Performance optimization authorization logic

As a backend developer at WhizCorp, you're part of a team responsible for a suite of microservices. One of these services is particularly critical, 
as it manages complex authorization logic. This microservice, built with Spring Boot and PostgreSQL, 
contains millions of records spread across several tables to align with business logic.

Given the complex nature of the permissions, the application makes extensive use of SQL joins and aggregation to calculate permission fields. 
Data updates occur frequently (multiple times an hour), and changes need to be reflected immediately to maintain security. 
However, as more users are added, the performance of this service is degrading. 
In fact, in certain scenarios, user login times extend to several minutes.

Your assignment is to identify potential causes of this issue and propose solutions to improve performance. 
You will be discussing your ideas with your teammates, Alice and Bob.


## Questions to get started

* What would be your initial approach to diagnosing and remedying this performance issue?
* What specific aspects of the service would you investigate in your analysis?
* Can you identify some areas that are typically known to cause performance bottlenecks in such a scenario?
* What general strategies would you consider if the performance issue isn't due to a single bottleneck but rather a combination of factors?