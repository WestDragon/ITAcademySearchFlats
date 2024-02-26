# Общее пояснение

Данный проект в первую очередь разработан для закрепления принципов проектирования и разработки бэкенда для современных веб-приложений.

На курсе было изучено:

- Работа c **HTTP**-протоколом:
    - Различия между **GET**, **POST**, **PUT**, **DELETE** запросами.
    - Способы передачи данных: **Query string**, **Headers**, **Body**
    - Принципы формирования URL по рекомендациям **RESTful API**
- Работа с **Базами данных** на примере **PostgreSQL**:
    - Различия между **DDL** и **DML**
    - **Транзакции**
    - Различие подходов разработки при использовании **JDBC** и **ORM**
- Работа с применением MVC что подразумевает разделение на слои
    - **Controller** - слой доступа в котором была реализована работа по протоколу **HTTP** через использование библиотеки **Spring Web MVC** внутри которого работает **DispatcherServlet**
    - **Service** - слой сервиса в котором была реализована бизнес логика и конвертации из **DTO** в **Entity**
    - **Dao** - слой доступа к данным в котором была реализована работа с **PostgreSQL** через использование библиотеки **Spring Data JPA**
- Работа с **Maven**
    - **pom.xml** - как файл с метаинформацией о проекте
    - Использование тэга **property** для создания переменных которые можно использовать в pom.xml
    - Автоматизированный запуск **JUnit** тестов через **maven-surefire-plugin**
    - Автоматический деплой **WAR** файла с использованием плагина **tomcat7-maven-plugin** и команды **mvn clean package tomcat7:deploy**
    - Использование **parent pom** для сборки нескольких **Maven проектов** подряд
- Написать про **Git**
- Написать про **Docker**
- Написать про **OpenAPI**

# Используемые технологии и фреймворки:
- [Java XX](https://docs.oracle.com/en/java/javase/17/docs/api/)
- [Maven](https://maven.apache.org/)
- [Spring Boot X.X.X](https://spring.io/projects/spring-boot)
- [Spring Data JPA X.X.X](https://spring.io/projects/spring-data-jpa)
- [Spring Security X.X.X](https://spring.io/projects/spring-security)
- [Spring Cloud X.X.X](https://spring.io/projects/spring-cloud)
- [MinIO](https://min.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/)
# Описание проекта: Агрегатор поиска жилья

Написать описание

# Дальнейшие планы:
