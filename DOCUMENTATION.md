# Документація API

## Модуль Calculator

### Функція add()
```python
def add(a, b):
    """Додавання двох чисел"""
    return a + b
```

**Параметри:**
- `a` (float): перше число  
- `b` (float): друге число  

**Повертає:**  
- `float`: суму чисел

**Приклад:**
```python
result = add(5, 3)
print(result)  # 8
```

---

### Функція divide()
```python
def divide(a, b):
    """Ділення двох чисел"""
    if b != 0:
        return a / b
    else:
        return "Помилка: ділення на нуль!"
```

**Параметри:**
- `a` (float): ділене  
- `b` (float): дільник  

**Повертає:**  
- результат ділення або текст помилки

**Приклад:**
```python
result = divide(10, 2)
print(result)  # 5.0
```
