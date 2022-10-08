# Python

* Что такое декоратор? Напиши декоратор, измеряющий время выполнения функции.
* Что такое аннотация типов? Какой модуль применяется?
* В чем отличие `is` от `==`?
* Какие существуют типы области видимости?
* Что такое `lambda`-функция? Как ее использовать с функциями `map()` и `filter()`?
* Как реализована обработка исключений? Что будет выведено после выполнения следующего кода:

<details><summary>Посмотреть код</summary>

```python
a = 1
try:
    a = 2
    print(a)
    raise Exception()
except:
    a = 3
    print(a)
    raise
else:
    a = 4
    print(a)
finally:
    a = 5
    print(a)
```

</details>

* Что такое виртуальная среда? Для чего нужен файл `requirements.txt`?
* Что такое `__new__`? В чем его отличие от `__init__`? В какой последовательности они выполняются?
* Что такое GIL? Почему его все еще используют?
* В чем отличие тредов от мультипроцессинга? В чем отличие `CPU-bound` операций от `I/O-bound`?

# Ресурсы
* [Декораторы в Python](https://tproger.ru/translations/demystifying-decorators-in-python/)
* [Введение в аннотации типов Python](https://habr.com/ru/company/lamoda/blog/432656/)
* [Область видимости в Python](https://python-scripts.com/scope)
* [Отличие `==` от `is`](https://qna.habr.com/q/346640)
* [Lambda-функции в Python](https://pythonru.com/osnovy/vse-chto-nuzhno-znat-o-lambda-funkcijah-v-python)
* [Обработка исключений и ошибок](https://pythonru.com/osnovy/znachenija-iskljuchenij-i-oshibok-v-python)
* [Виртуальная среда](https://python-scripts.com/virtualenv)
* [Магический метод `__new__`. Пример паттерна Singleton](https://www.youtube.com/watch?v=-xoT6rntpK0&t=624s)
* [Python Global Interpreter Lock и как он работает](https://tproger.ru/translations/global-interpreter-lock-guide/)
