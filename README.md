Отчёт о тестировании KeyValidator
Приложение KeyValidator распространяется в виде файла KeyValidator.class, предназначенного для работы на платформе Java 8+.
3.11.2020 г. было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 0 часов 30 мин.

В результате тестирования выявлены следующие дефекты:
Валидный ключ не проходит проверку
https://github.com/urop9xa/-1---KeyValidator/issues/1
Валидный ключ не проходит проверку 
https://github.com/urop9xa/-1---KeyValidator/issues/2
Невалидный ключ проходит проверку
https://github.com/urop9xa/-1---KeyValidator/issues/3

Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

Файл KeyValidator.class https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class
Файл .gitignore  https://github.com/netology-code/javaqa-homeworks/blob/master/.gitignore
В качестве тестовых данных использовались данные Руководство использования KeyValidator :
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md
1 Валидные ключи :

8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
80b427f8-92cd-3aae-ba04-3927fbe17c6
b295bc63-9f03-3b4b-af80-969b39f8c262
387eedc6-12e9-3b32-9881-63b6b5e85317
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180
2 Невалидные ключи:

18252235-78e0-44a5-8720-556f0c7da17a
e66075b6-ddad-445e-baf6-161b3289522b
b6d53250-f07e-4352-a293-6102ddf7f1ca
c2bc778a-1cb9-46c6-b435-0489649d2a42
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1
При вводе в приложении валидных ключей должно появится "ОК", при вводе невалидных - "FAIL".

Тестирование производилось в следующем окружении:

Windows 10 Home x64
Java Version 11