# Отчёт о тестировании KeyValidator

## Краткое описание

02.03.2021 - 02.03.2021 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Ключи из списка валидных являются невалидными](https://github.com/AlexandraPyaterikova/Javaqa-1.1_1/issues/1)
* [Ключ из списка невалидных является валидным](https://github.com/AlexandraPyaterikova/Javaqa-1.1_1/issues/3)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)


В качестве тестовых данных использовались данные [Руководство использования](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 валидный ключ
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 валидный ключ
* b295bc63-9f03-3b4b-af80-969b39f8c262 валидный ключ
* 387eedc6-12e9-3b32-9881-63b6b5e85317 валидный ключ
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 валидный ключ
* 18252235-78e0-44a5-8720-556f0c7da17a невалидный ключ
* e66075b6-ddad-445e-baf6-161b3289522b невалидный ключ
* b6d53250-f07e-4352-a293-6102ddf7f1ca невалидный ключ
* c2bc778a-1cb9-46c6-b435-0489649d2a42 невалидный ключ
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 невалидный ключ

Тестирование производилось в следующем окружении:
* Windows 10 corporate x64
* Java 11.0.10

