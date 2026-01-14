# Booker API Test Report
In this project I have performed API automation testing on [Restfull Booker API](https://restful-booker.herokuapp.com). To perform the tests I used Postman API Testing Tool.

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Shop_API_Manan_Ahmed_Broti.postman_collection.json -e Shop_API_Manan_Ahmed_Broti.postman_environment.json
```
- Run Command for Report: 
```console 
newman run Shop_API_Manan_Ahmed_Broti.postman_collection.json -e Shop_API_Manan_Ahmed_Broti.postman_environment.json -r cli,htmlextra
```
- Run Command for Report With Iteration: 
```console 
newman run Shop_API_Manan_Ahmed_Broti.postman_collection.json -e Shop_API_Manan_Ahmed_Broti.postman_environment.json -n "number of iteration" -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## Conclusion & More
In this API test project, I have tested all the API routes & performed effective tests. To learn more about APIs & HTTP requests you can read my blogs/posts:
- [Understanding API Concepts](https://ahmedmanan.com/understanding-api-concepts/)
- [HTTP Fundamentals](https://ahmedmanan.com/http-fundamentals/)
