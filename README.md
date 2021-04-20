# bookstore_server
A bookstore server using REST api, springframework, jdbc for database connection and thirdparty PostgreSQL hosting for data storage.

## Technologies
* Java
* Maven
* Spring
* PostgreSQL
* JDBC

## Some of REST api endpoints

| Method  |       URL                    |  Request body                          | Response body | Comment
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| POST    |      /ksiegarnia/loginAdmin  |{"login": "admin","password": "admin" } | None          | Login as admin
| GET    |      /ksiegarnia/ksiazki  |None | {"idKsiazki": "16","tytul": "Pragmatyczny Programista","autor": "Andrew Hunt","wydawnictwo": "Helion Warszawa","temat": "Biznes IT","jezykKsiazki": "angielski","rokWydania": "2011","dostepnosc": "t","opis": "Od ambitnego do najlepszego….","imieAutora": "Andrew","nazwiskoAutora": "Hunt"}| Get all books from database
| DELETE    |      /ksiegarnia/klient/usunkonto?login=login123&pass  |login, password | None          |Deletes an account|


...And 15 more
