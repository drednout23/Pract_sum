# Программы на Python

Этот репозиторий содержит несколько небольших программ на Python для различных задач.

## 1. Реверс строки

Программа принимает строку и возвращает её в обратном порядке.

### Код

def backward_string(val: str) -> str:
    return val[::-1]
    return None

print("Example:")
print(backward_string("val"))

# Эти "asserts" используются для самопроверки
assert backward_string("val") == "lav"
assert backward_string("") == ""
assert backward_string("ohho") == "ohho"
assert backward_string("123456789") == "987654321"

print("The mission is done! Click 'Check Solution' to earn rewards!")

### Пример использования

$ python backward_string.py
Example:
lav
The mission is done! Click 'Check Solution' to earn rewards!

## 2. Остаток от деления

Программа принимает два целых числа и возвращает остаток от деления первого числа на второе.

### Код

def find_remainder(dividend: int, divisor: int) -> int:
    return dividend % divisor
    return 0

print("Example:")
print(find_remainder(3, 2))

# Эти "asserts" используются для самопроверки
assert find_remainder(10, 3) == 1
assert find_remainder(14, 4) == 2
assert find_remainder(27, 4) == 3
assert find_remainder(10, 5) == 0
assert find_remainder(10, 1) == 0
assert find_remainder(5, 7) == 5
assert find_remainder(7, 5) == 2

print("The mission is done! Click 'Check Solution' to earn rewards!")

### Пример использования

$ python find_remainder.py
Example:
1
The mission is done! Click 'Check Solution' to earn rewards!

## 3. Определение знака числа

Программа принимает целое число и возвращает строку "positive", "negative" или "zero" в зависимости от знака числа.

### Код

def determine_sign(num: int) -> str:
    if num > 0:
        return "positive"
    elif num < 0:
        return "negative"
    else:
        return "zero"
    return ""

print("Example:")
print(determine_sign(11))

# Эти "asserts" используются для самопроверки
assert determine_sign(5) == "positive"
assert determine_sign(0) == "zero"
assert determine_sign(-10) == "negative"
assert determine_sign(1) == "positive"
assert determine_sign(-1) == "negative"
assert determine_sign(999) == "positive"
assert determine_sign(-1000) == "negative"
assert determine_sign(123456789) == "positive"
assert determine_sign(-987654321) == "negative"
assert determine_sign(2) == "positive"

print("The mission is done! Click 'Check Solution' to earn rewards!")

### Пример использования

$ python determine_sign.py
Example:
positive
The mission is done! Click 'Check Solution' to earn rewards!

## 4. Проверка четности числа

Программа принимает целое число и возвращает `True`, если число четное, и `False` в противном случае.

### Код

def is_even(num: int) -> bool:
    return num % 2 == 0
    return None

print("Example:")
print(is_even(2))

# Эти "asserts" используются для самопроверки
assert is_even(2) == True
assert is_even(5) == False
assert is_even(0) == True

print("The mission is done! Click 'Check Solution' to earn rewards!")

### Пример использования

$ python is_even.py
Example:
True
The mission is done! Click 'Check Solution' to earn rewards!

## 5. Сумма и произведение

Программа вычисляет сумму и произведение двух заданных чисел и выводит результат.

### Код

a = 2
b = 5

add = a + b
multi = a * b

print(f"Сума a і b: {add}")
print(f"Добуток a і b: {multi}")

### Пример использования

$ python add_multiply.py
Сума a і b: 7
Добуток a і b: 10
