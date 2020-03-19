## Отчёт о тестировании приложения "Precision"
# Краткое описание
При сложении двух конечных десятичных дробей образуется бесконечная дробь

# Описание теста
Функциональное тестирование (проверка того, насколько математически правильным будет результат сложения двух чисел примитивного типа double (первая переменная - 0,3, вторая переменная - 0,6).

# Результаты
100% не успешных тестов для данных двух чисел.

# Ссылки на баг-репорты

https://github.com/Nata-AMI/2_3_java/issues/2

# Общие рекомендации
Рекомендации тестировщика по итогам тестирования
Проверки на умножение, вычитание такого бага не дают, так же как и сложение цифр 0,3+0,3, или 0,6+0,6. Почему то ошибка появляется только при сочетании 0,6+0,3

 
