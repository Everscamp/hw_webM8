Файл models описує моделі для зберігання даних із цих файлів у колекціях author та quote.
Seeds завантажує json файли у хмарну базу даних, поле автора є Reference fields поле, де зберігається ObjectID з колекції authors.
У файлі main.py реалізований скрипт для пошуку цитат за тегом, за ім'ям автора або набором тегів. Скрипт виконується в нескінченному циклі і за допомогою звичайного оператора input приймає команди у наступному форматі команда: значення

Скрипти consumer.py і producer.py використовуючи RabbitMQ, за допомогою черг імітують email-розсилку контактам.
Поле is_sent в моделі contact має значення False за замовчуванням і стає True, коли повідомлення буде відправлено. 