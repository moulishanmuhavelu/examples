This is a sample Spring boot integrated with Swagger API.

Swagger ui will be started during the application startup
Swagger ui can be accessed in the same port with "swagger-ui.html"
 For Ex: A server running in 8080 in localhost can be accessed as http://localhost:8080/swagger-ui.html

For the path variables in url, genericModelSubstitutes(Optional.class) should be added in Docket object