### Switch-case
```python
match var:
    case 1: pass  # Соответствие значению
    case 2 | 3: pass  # Соответствие ИЛИ
    case int(): pass  # Соответствие классу
    case [a, b]: pass  # Сопоставление по длине
    case _: pass  # Значение по умолчанию
```

### lambda
```python
def foo(x):
    return lambda y: y ** x

print(foo(2)(2))
```


### for
Для перебора словаря в виде ключ-значение используют `dict.items()`. Для перебора списка в виде ключ-значение используют `enumerate(list)`. Для перебора нескольких списков одновременно используют `zip(list1, list2)`. Для перебора обратной последовательности используют `reversed(...)`. Для перебора отсортированной последовательности используют `sorted(...)`.