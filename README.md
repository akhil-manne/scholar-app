# scholar-app
This is an assignment submission application, in which teachers create assignments and students submit their submissions for the created assignments. Teachers can then evaluate the submissions and assign results and students can view their results. There would also be an admin, who would create teacher and student accounts.
For the frontend all the files necessary are provided. But, for the backend, only the controller, model, repository, service class files along with the application.properties file (responsible for connecting to the MySQL database) and pom.xml file (contains all the necessary dependencies and plugins required to run the spring boot application) have been provided. 
In the actual process, a maven project folder needs to be downloaded from the spring initializr website (https://start.spring.io/), which would contain all the required files (including application.properties and pom.xml as well), even the ones not mentioned here.
One more thing to note, all the tables in the MySQL database will be created automatically by the spring boot backend code. But, the admin table needs to be created manually with the fields 'id', 'name', and 'password', to login as an admin.
