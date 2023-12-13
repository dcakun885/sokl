def sum_numbers(numbers):
    """Функция для суммирования чисел в списке."""
    total = sum(numbers)
    return total

if __name__ == "__main__":
    # Пример использования функции
    numbers_list = [1, 2, 3, 4, 5]
    result = sum_numbers(numbers_list)
    print(f"Сумма чисел в списке {numbers_list}: {result}")