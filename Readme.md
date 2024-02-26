
## Technologies used
ReactJS -
Spring Boot -
Spring Security -
JWT -
MySQL -

## start the backend

1. **Clone the application**

	```bash
	git clone 
	cd polling-app-server
	```

2. **Create MySQL database**

	```bash
	create database polling_app
	```

3. **Change MySQL username and password as per your MySQL installation**

	+ open `src/main/resources/application.properties` file.

	+ change `spring.datasource.username` and `spring.datasource.password` properties as per your mysql installation

4. **Run the app**

	Run the spring boot backend -

	```bash
	mvn spring-boot:run
	```

	The server will start on port 8000.

	You can also package the application in the form of a `jar` file and then run it like so -

	```bash
	mvn package
	java -jar target/polls-0.0.1-SNAPSHOT.jar
	```


## Start the frontend 

Change the directory to `polling-app-client` folder -

```bash
cd polling-app-client
```

Install dependencies -

```bash
npm install
```

Start the client -

```bash
npm start
```

## The front-end server will start on port 3000.
