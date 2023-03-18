# Habr analogue

## Description
Collective blog like habr.com

## Video presentation of project
https://cloud.mail.ru/home/Desktop%202022.12.13%20-%2014.19.43.02.mp4?weblink=FHJ4%2FtWNzWoFmp

## Tools and technologies used in project
- Java 11
- Spring Boot 2.7.3
- PostgreSQL
- Liquibase
- Gradle
- HTML
- Thymeleaf
- JavaScript
- Docker

## Tools needed for launching project
- Java 11 or higher
- Docker 3.8
- Gradle 7.5

## Instruction for launching project
- download project from GitHub
- open project folder by IntelliJ IDEA
- start Docker
- fulfill the following command in the terminal: docker-compose up -d
- run src/main/java/ru/gb/hubr/HubrApplication.java
- open internet browser and enter URL http://localhost:8080/articles/all
- user’s credentials for testing application: login: system password: password

## Описание приложения
Сайт коллективного блога наподобие habr.com

## Видео-презентация проекта
https://cloud.mail.ru/home/Desktop%202022.12.13%20-%2014.19.43.02.mp4?weblink=FHJ4%2FtWNzWoFmp


## Инструменты и технологии, использованные при создании проекта
- Java 11
- Spring Boot 2.7.3
- PostgreSQL
- Liquibase
- Gradle
- HTML
- Thymeleaf
- JavaScript
- Docker

## Программное обеспечение, необходимое для запуска проекта
- Java Development Kit 11 и выше;
- Docker 3.8
- Gradle 7.5

## Инструкция по запуску приложения
- клонировать проект из github
- через терминал в папке проекта выполнить команду: docker-compose up -d для запуска контейнера с базой данных приложения
- запустить терминал из папки с проектом и выполнить gradlew.bat clean build сборки war-архива с приложением (war-архив hubr-0.0.1-SNAPSHOT.war должен быть создан в папке build/libs проекта)
- запустить терминал из папки build/libs проекта и выполнить команду java -jar hubr-0.0.1-SNAPSHOT.war для запуска приложения

## Инструкция по работе с приложением
- чтобы зайти на главную страницу приложения, введите в строке браузера: http://localhost:8080/articles/all
- зайти в приложение в качестве зарегистрированного пользователя, используйте следующие данные: логин: system, пароль: password
- чтобы завершить работу приложения, необходимо закрыть окно терминала из п. 4 с запущенным приложением
