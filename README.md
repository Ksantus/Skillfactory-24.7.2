Задание 24.7.2 QAP-214

В директории /tests располагается файл с тестами

В директории /tests/images лежат картинка для теста добавления питомца и теста добавления фото питомца, а также текстовый файл для проверки возможности создания карточки питомца с фото недопустимого формата.

В корневой директории лежит файл settings.py, куда из файла .env, также расположенного в корневой директории, импортируются: валидные и невалидные логин и паролеь, а также несуществующий ключ аутентификации.

В корневой директории лежит файл api.py, который является библиотекой к REST API сервису веб-приложения Pet Friends.

Библиотека api написана в классе, что соответствует принципам ООП и позволяет удобно пользоваться её методами. При инициализации библиотеки объявляется переменная base_url которая используется при формировании url для запросов.

Методы имеют подродное описание.

Тесты проверяют работу методов, используя api библиотеку.
