## To Do App
It creates the to do list.<br>
*I Created this multi-container application which has a client (React), a server (Node.js)and a database instance (Postgres).*<br>
This project is created for Docker Training under IIEC_Connect(An Initiative by Vimal Daga Sir)

## How To Run
1. To get the containers up and running
```
$ docker-compose up -d
```

2. To check the running containers
```
$ docker container ls
```
![running containers](img/1.png)

3. Now, we create some to do items using Postman. 
![creating items](img/2.png)
 ```
 Running the GET request to:
 http://localhost:3001/v1/items
 ```
![creating more items](img/3.png)

4. To get a bash shell in the container.
 ```
 docker exec -it ad947a6b302 bash
 ```
 
5. To connect to the postgres database with the default credentials
 ```
psql -U postgres
```
![check Table Exist](img/4.png)

6. Testing client application

![Client application](img/5.png)

## Ultimate Hierrachy

├── client<br>
├── server<br>
├── img<br>
├── Readme.md<br>
└── docker-compose.yml<br>

Atlast, I thank Vimal Daga Sir for their directions and motivation.
