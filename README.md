python
Copy code
# Функция, которая складывает два числа
def add(x, y):
    return x + y

# Функция, которая вычитает два числа
def subtract(x, y):
    return x - y

# Функция, которая умножает два числа
def multiply(x, y):
    return x * y

# Функция, которая делит два числа
def divide(x, y):
    return x / y

print("Выберите операцию.")
print("1. Сложение")
print("2. Вычитание")
print("3. Умножение")
print("4. Деление")

# Запрос пользователю ввода операции
choice = input("Введите номер операции (1/2/3/4): ")

num1 = float(input("Введите первое число: "))
num2 = float(input("Введите второе число: "))

if choice == '1':
    print(num1,"+",num2,"=", add(num1,num2))

elif choice == '2':
    print(num1,"-",num2,"=", subtract(num1,num2))

elif choice == '3':
    print(num1,"*",num2,"=", multiply(num1,num2))

elif choice == '4':
    print(num1,"/",num2,"=", divide(num1,num2))

else:
    print("Неверный ввод")
