# SF_Final_Project 2023

ИТОГОВЫЙ ПРОЕКТ ПО АВТОМАТИЗАЦИИ ТЕСТИРОВАНИЯ

Тестирование формы авторизации Личного кабинета Ростелеком https://b2c.passport.rt.ru

Протестированы требования к проекту и разработаны тест-кейсы для формы авторизации Личного кабинета Ростелеком

https://docs.google.com/spreadsheets/d/196p4U1Xz5MpOeT0rVKC1C2VLoNlRIMiM9o2wtOgMi9o/edit?usp=sharing

base_data.py - базовые классы, процедуры, функции и локаторы для автотестов

settings.py - регистрационные данные для позитивных тестов авторизации

test_SF_RT_passport - собственно набор автотестов, нумерация соответствует номеру тест-кейса

запуск автотестов (драйвер в одной папке с тест-скриптом)

python -m pytest -v --driver Chrome --driver-path chromedriver.exe test_SF_RT_passport.py

