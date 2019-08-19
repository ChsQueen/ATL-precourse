# Cognizant-ATL-precourse

## BARE MINIMUM REQUIREMENTS
Bare minimum requirements are absolutely required. 

* Using [start.spring.io](start.spring.io) create application/RESTful api (if this is foreign to you, a tutorial like this one walks through creating an application and will be helpful)
* Create at least one entity and repository backed by the database of your choice (MySql, PostgreSql, etc)
* Write unit tests for each enpoint before creating the end point. [MockMvc](https://spring.io/guides/gs/testing-web/) is a great api for this.
* Implement endpoints for full crud functionality, Create (POST/PUT), Read (GET), Update (POST/PUT), and Delete (DELETE)
* Consider using a service layer to abstract the implementation from the interface.  At least, know why this is a good idea.
* Push your project to GitHub, send us a link (via Slack is fine).  
* Complete this Docker tutorial [HERE](https://github.com/dylanlrrb/Please-Contain-Yourself)


## ADVANCED
Our advanced content is intended to throw you in over your head, requiring you to solve problems with very little support or oversight.

* Dockerize the application you wrote
* Push that Docker image to a [Docker Hub public repository](hub.docker.com), send link (via Slack is fine)


## NIGHTMARE MODE
Nightmare mode is exactly what it sounds like: difficult. 

* Deploy your Dockerized application to a cloud provider of your choice (Heroku, Digital Ocean, AWS, Google, PCF, etc)
* Send screenshot proof of success (via Slack is fine).  Better yet, send us a link to your working api.
* BEWARE of charges - be sure to spin down when you’re done. We will not reimburse you for charges incurred (but Amazon probably will if you accidentally do this incorrectly).
