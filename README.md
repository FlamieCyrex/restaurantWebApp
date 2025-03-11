# Restaurant Vote System (VTS)

## This project is implemented for voting by users to decide the best restaurant for dinner. It features a voting system to choose the best restaurant. Each day, restaurant menus are updated, and the voting is time-sensitive.

### Project requirements:

Design and implement a REST API using Hibernate/Spring/SpringMVC (Spring Boot preferred!) without a frontend.


The task is
Build a voting system to decide where to have lunch.
Two types of users: admin and regular users.
The admin can input a restaurant and its lunch menu for the day (usually 2-5 items, just the dish name and price).
The menu changes daily (admins are responsible for updates).
Users can vote for a restaurant where they want to have lunch today.
Only one vote is counted per user.
If a user votes again on the same day:
If it is before 11:00, we assume they changed their mind.
If it is after 11:00, it’s too late, and the vote cannot be changed.
Each restaurant provides a new menu every day.
As a result, provide a link to the GitHub repository. It should contain the code, a README.md with API documentation, and a couple of curl commands to test it (preferably with a link to Swagger).


## Stack
* Java 21
* Spring Boot 2.x
* Hibernate
* Maven
* HSQLDB
