[![GitHub Release](https://img.shields.io/github/v/release/Macegor/fint)](https://github.com/Macegor/fint/releases)
[![GitHub License](https://img.shields.io/github/license/Macegor/fint)](https://github.com/Macegor/fint/blob/main/LICENSE)
[![OneScript](resources/oscript.svg)](https://github.com/EvilBeaver/OneScript)

# Fint - фреймворк, реализующий ООП (Наследование, Инкапсуляция, Полиморфизм) и статическую типизацию в OneScript

![Logo](resources/logo.png)

Анонсы, обсуждение и обмен опытом:
[![Telegram](resources/Telegram.png)](https://t.me/fint_onescript)

## Возможности

- Разделение контекста: теперь не обязательно следить за уникальностью имён классов.
- Строгая типизация свойств классов, параметров методов и возвращаемых значений.
- Реализованы принципы ООП:
  - Наследование — один класс может расширить другой.
  - Инкапсуляция — модификаторы доступа, контролирующие доступ к свойствам (генерация геттеров и сеттеров).
  - Полиморфизм — дочерний класс может переопределять поведение родительского.
- Интерфейсы
- Разработка библиотек для приложений, основанных на Fint, с использованием Fint.

## Планы по развитию

- Несколько типов (сейчас доступен только `Любой`).
- Алиасы имён импортируемых классов.
- Встроенный DI-фреймворк (классическая реализация).
- Декораторы.
- Делегаты и анонимные функции.
- Асинхронность.
- Обходимые классы.
- Объекты «листы» для каждого класса.

## Документация

- [Установка](docs/installation.md)
- [Синтаксис](docs/syntax.md)
- [Отладка](docs/debugging.md)
- [Введение](docs/introduction.md)
- [Пространства имен и импортирование](docs/namespaces.md)
- [Создание экземпляров объектов](docs/instantiation.md)
- [Создание свойств, методов и их типизация](docs/typing.md)
- [Работа с свойствами](docs/properties.md)
- [Работа с методами](docs/methods.md)
- [Наследование](docs/inheritance.md)
- [Интерфейсы](docs/interfaces.md)
- [Перечисления](docs/enumeration.md)
