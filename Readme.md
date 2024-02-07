# Дипломный проект профессии «Инженер по тестированию»

* ***[Требования к заданию](https://github.com/netology-code/qamid-diplom/blob/main/README.md)***

## Описание

Автоматизация тестирования мобильного приложения "Мобильный хоспис".

Приложение предоставляет функционал по работе с претензиями хосписа и включает в себя:

1. Информацию о претензиях и функционал для работы с ними.
2. Новостную сводку хосписа.
3. Тематические цитаты.

## Документация

* ***[Plan](https://github.com/ArthurPetrosov/QA_Diploma)***

* ***[Check-list](https://github.com/ArthurPetrosov/QA_Diploma)***

* ***[Test-cases](https://github.com/ArthurPetrosov/QA_Diploma)***

* ***[Bugs issues](https://github.com/ArthurPetrosov/QA_Diploma)***

* ***[Allure results](https://github.com/ArthurPetrosov/QA_Diploma)***

* ***[Report](https://github.com/ArthurPetrosov/QA_Diploma)***

## Тестового окружение

1. [Склонировать](https://github.com/ArthurPetrosov/QA_Diploma) на рабочую станцию
2. Запутсить **Android Studio** и открыть папку **fmh-android** 
3. Выбрать эмулятор с **Android API 29 в качестве тестового устройства. 


## Запуск тестов

Запустить тесты консольной командой **./gradlew connectedAndroidTest** или выбрать пункт контекстного меню **Run 'All Tests'**, или нажать **Shift+Ctl+R**


## Создание отчета Allure

1. После завершения выгрузить каталог /data/data/ru.iteco.fmhandroid/files/allure-results с эмулятора (при помощи Device Manager)
2. Для отчета выполнить в терминале команду **allure serve**