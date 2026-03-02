# TODO-"записная книжка" из JavaRush.

Проект не мой, скачал откуда-то.

CRUD приложение использует spring-boot-starter-web и template __Thymeleaf__. 
Данные хранятся в базе MySQL, обмен проходит 
с помощью query-запросов и организует фильтрацию, сортировку по значениям, 
регулируемую с помощью элементов управления в пользовательском интерфейсе.

- Использован template Thymeleaf (__очень симпатичный__ Bootstrap интерфейс с доработанным css). 
- Постраничная навигация. 
- Редактирование записи.
- Переход по страницам.

![Начальный экран](doc/notebook_start.png)

![Редактирование записи](doc/notebook_edit.png)

![На телефоне](doc/notebook_mobile.jpg)

### Сборка и запуск приложения

Используется Java 8.

Сборка:
````shell
./mvnw clean package
````

Запуск:

[./run_jar.sh](./run_jar.sh)

````shell
/usr/lib/jvm/java-1.8.0-openjdk-amd64/bin/java -jar target/Notebook-0.0.1-SNAPSHOT.jar
````

Открыть [http://127.0.0.1:8080/](http://127.0.0.1:8080/)

### Ссылки
- [Material CSS materializecss.com](https://materializecss.com/buttons.html)