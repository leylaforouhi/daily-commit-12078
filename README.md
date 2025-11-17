def separate_even_odd(numbers):
    evens = [n for n in numbers if n % 2 == 0]
    odds = [n for n in numbers if n % 2 != 0]
    return evens, odds

if __name__ == "__main__":
    nums = [12, 7, 4, 9, 20, 33, 42]
    even_list, odd_list = separate_even_odd(nums)
    print(f"Even numbers: {even_list}")
    print(f"Odd numbers: {odd_list}")
