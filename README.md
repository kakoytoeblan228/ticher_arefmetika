import random
print('Привет дорогой ученик,сегодня будем учиться арифметике.')
yes_or_no = input('ты знаешь что такое + - / * и как это всё работает')
if yes_or_no == 'да':
    print('хорошо,будет только практика потомучто повторение мать учения.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет', num1, '+', num2)
        num3 = int(input())
        if num3 == num2 + num1:
            print('малодечик,правельно.')
        else:
            print('не правельно,но ничего страшного ошибаются все.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет', num1, '-', num2)
        num3 = int(input())
        if num3 == num2 - num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет', num1, '*', num2)
        num3 = int(input())
        if num3 == num2 * num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет', num1, '/', num2)
        num3 = int(input())
        if num3 == num2 / num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    print("Урок окончен!")
else:
    print('Операция сложения обозначается знаком «плюс» (+) и используется, когда складывают числа,например 1 + 1 = 2 ')
    print('хорошо продолжаем')
    plys = int(input('сколько будет 2 + 2 \n'))
    if plys == 4:
        print('малодечик,правельно.')
    else:
        print('не правильно,но ничего страшного ошибаются все.')
    print('Операция вычитания обозначается знаком «минус» (−) и используется когда из одного числа вычитают другое, например 4 - 2 = 2')
    minys = int(input('сколько будет 8 - 2 \n'))
    if minys == 6:
        print('малодечик,правельно.')
    else:
        print('не правильно,но ничего страшного ошибаются все.')
        print('Обозначается знаком умножения (×) и используется когда одно число умножается на другое. Слово умножение говорит само за себя — какое-то число увеличивается в определенное количество раз, то есть множится,например 2 * 2 = 4')
    ymnocgit = int(input('сколько будет 4 * 5\n'))
    if ymnocgit == 20:
        print('малодечик,правельно.')
    else:
        print('Обозначается знаком деления (÷ или : ) и используется когда делят числа,например 50 / 5 = 10')
        print('не правильно,но ничего страшного ошибаются все.')
    rusdelit = int(input('сколько будет 14 / 2 \n'))
    if rusdelit == 7:
        print('малодечик,правельно.')
    else:
        print('не правильно,но ничего страшного ошибаются все.')
        print('а теперь практика')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет',num1,'+',num2)
        num3 = int(input())
        if num3 == num2 + num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('скольк будет',num1,'-',num2)
        num3 = int(input())
        if num3 == num2 - num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет',num1,'*',num2)
        num3 = int(input())
        if num3 == num2 * num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    for _ in range(10):
        num1 = random.randint(1, 10)
        num2 = random.randint(1, 10)
        print('сколько будет',num1,'/',num2)
        num3 = int(input())
        if num3 == num2 / num1:
            print('малодечик,правельно.')
        else:
            print('не правильно,но ничего страшного ошибаются все.')
    print("Урок окончен!")
