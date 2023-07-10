# demoBackgroundSync


To run the example, you first have to start the server:

```Shell
cd server
./mvnw spring-boot:run
//or on Windows
.\mvnw.cmd spring-boot:run
```

Then build and run the client

```Shell
cd clientng
npm -i
ng build --configuration production
http-server ./dist/app -c-1 -o
```

