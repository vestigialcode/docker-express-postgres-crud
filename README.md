# docker-express-postgres-crud

![docker-express-postgres-crud](https://user-images.githubusercontent.com/54473532/139152478-5c48c83f-49f7-4e1f-a721-ff8393f32d92.gif)


Its api first demo of taking input , getting the input,update input and finally delete the input <br/>

[![License](https://img.shields.io/github/license/Massad/gin-boilerplate)](https://github.com/vestigialcode/docker-express-postgres-crud/blob/main/LICENSE)
## FILE FORMAT SUPPORTS
1. Text ❎ <br/>
2. PDF ❎ <br/>
3. CSV ❎<br/>
4. VIDEO(mp4) ❎<br/>
 
 ## How to test
 TO get any specific file input
 ```
 http://localhost:3000/<FILE_FORMAT>
 ``` 
 for example to test with video format try  
 ```
 http://localhost:3000/video
 ``` 
 and for text format try 
 ```
 http://localhost:3000/text
 ```
 
 ## How to run
  
 Before running make sure docker in installed in your system. Follow  https://docs.docker.com/engine/install/ to install in your system.After installing docker follow the commands.
 ```
$ git clone https://github.com/vestigialcode/docker-express-postgres-crud.git
```

```
$ cd docker-express-postgres-crud
```

```
$ docker-compose up
```



After this the docker will run at port 3000. Congratultions you are all set. Now go to `http://localhost:3000` 

## How to stop

```
docker-compose stop
```
to remove all the builds 
```
docker-compose rm -v
```




