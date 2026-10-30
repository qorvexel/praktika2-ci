# Простой калькулятор

Версия: 1.0.0.

Модуль calculator.py содержит две функции:
- add(a, b) — сложение двух чисел;
- multiply(a, b) — умножение двух чисел.

## Пример использования

```python
from calculator import add, multiply

print(add(2, 3))       # 5
print(multiply(3, 4))  # 12
```

## Запуск тестов

```bash
python -m unittest discover -v
```

## Генерация документации

HTML-документация создаётся из описаний модуля и функций:

```bash
python -m pydoc -w calculator
```

Результат — файл calculator.html, который можно открыть в браузере.
