﻿# Тестирование сайта Ростелеком

### Используемые библиотеки
Для создание данных автотестов применялись библиотеки: 
 - **selenium** (Для возможности тестирования сайта Ростелекома)
 - **pytest** (Для автоматизации тестирования по частям)
 - **time** (Для вынужденных временных остановок кода)
 
### Применяемые технологии
В данном коде были использованы различные технологии и приемы, для упрощения кода и лучшей структуризации.
Среди них:
 - Использование вспомогательной функции *input_reg_par* для удаления повторяющихся элементов кода.
 - Задача изменяемых переменных кода в начале и удобное их редактирование.

## Что нужно сделать для запуска
Для запуска программы требуется:

 - Установленная версия python 3.3 
 - Установленные библиотеки в сам python или в виртуальное окружение
 - Webdriver для вашей версии браузера (выбрать и скачать нужную версию можно [здесь](https://chromedriver.chromium.org/downloads))

## Описание автотестов 
 2. Проверяем наличие логотипа сбоку после нажатия кнопки для регистрации
 3. Проверяем процесс регистрации
 4. Пытаемся зарегистрироваться с паролем из 5 символов
 5. Пытаемся зарегистрироваться с паролем только из строчных букв
 6. Пытаемся зарегистрироваться с паролем из ру-символов
 7. Пытаемся зарегистрироваться с паролем и не таким же паролем в графе "подтверждение пароля"
 8. Пытаемся зарегистрироваться на уже существующий email
 9. Пытаемся зарегистрироваться на уже существующий телефон
 10. Авторизация с помощью телефона
 11. Попытка авторизации через телефон с неправильным телефоном
 12. Попытка авторизации через телефон с пустым телефоном
 13. Авторизация с помощью email
 14. Попытка авторизации через email с неправильным email
 15. Попытка авторизации через email с пустым email
 16. Попытка авторизации через login с неправильным login
 17. Попытка авторизации через login с пустым login
 18. Попытка авторизации через bill с неправильным bill
 19. Попытка авторизации через bill с пустым bill
 20. Попытка изменить пароль с помощью "восстановление пароля" на пароль с 5 символами
 21. Попытка изменить пароль с помощью "восстановление пароля" на пароль такой же, как и предыдущий
 22. Попытка изменить пароль с помощью "восстановление пароля" на пароль с ру-символами