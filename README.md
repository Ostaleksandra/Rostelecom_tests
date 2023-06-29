# Rostelecom_tests
Тест-кейсы и автотесты для проекта Ростелеком https://b2c.passport.rt.ru

При составлении тест-кейсов использовались техники тест-дизайна:
-предугадывание ошибок
-граничные значения
-негативное тестирование
-метод "черного ящика"

Тест-кейсы и баг-репорты:
https://docs.google.com/spreadsheets/d/18NESWsa1Hr4gW-bvYOqCdlZPAq0lNXr1fh4FGCIBrsg/edit?usp=sharing

Использовались библиотеки selenium, pytest, pytest-selenium

Для запуска необходимо набрать в терминале pytest -v --driver Chrome --driver-path C:\Users\71601088\PycharmProjects\pythonProject14chromedriver.exe test_rostelecom.py
