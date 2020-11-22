# ui-to-database
Java app which will process the inputs from user coming from UI and process, and then save it to the database. 

#Running locally
- Clone the application and set up locally 
- No authorization necessary
- Build successfully and run
- For database to H2, connect to http://localhost:8080/h2-console
- Perform operations through POSTMAN or Rest Client 

# Performing CRUD operations

## For POST and PUT: 
- body{
"name":"String",
"number":"String",
"id":null;
}

# To create Docker image 
- export ENV=dev
- export ENV_CONFIG=dev
- export SPRING_PROFILES_ACTIVE=dev
- docker build -t <tag name:tag version> <Dockerfile path>
- docker run -e ENV -e ENV_CONFIG -e SPRING_PROFILES_ACTIVE <tag name:tag version>
