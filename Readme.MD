

## Routes:

## URLs


## App 1
    POST /quiz
    GET  /quiz
    GET /quiz/id


##  App 2
    POST /question
    GET  /question
    GET  /question/questionId
    GET  /question/quiz/quizId

## main domain: localhost

    App 1 port: 8081  quiz service		client: http://localhost:8761/eureka/
    App 2 port: 8082  question service  client: http://localhost:8761/eureka/
    App 3 port: 8761  config server
    App 4 port: 8083  API getway

## Eureka server host : http://localhost:8761/

    Automatic load balancer using spring boot 3, Spring Cloud, API gateway and Eureka discovery servers.

## Mysql DB using docker

sudo docker-compose up
user: user
password: password
rootpassword: password
