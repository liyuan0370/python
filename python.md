
from functools import reduce
import math
import matplotlib.pyplot as plt
import numpy as np



 while True:

    print("Добро пожадовать")
    print("Введите '1.1' для вычисления суммы for-циклом")
    print("Введите '1.2' для вычисления суммы с while-циклом")
    print("Введите '1.3' для вычисления суммы рекурсией")
    print("Введите '2' для вычисления степени двойки")
    print("Введите '3' для вычисления cреднего арифметического")
    print("Введите '4' для вычисления номера числа в последовательности Фибоначчи")
    print("Введите '5' для вычисления факториала")
    print("Введите '6' для замены максимального на минимальное и наоборот")
    print("Введите '7' для нахождения расстояния между точками")
    print("Введите '8' для построения  графика траектории снаряда")
    print("Введите '0' для выхода")


    user_input = input(":")

    if user_input == "0":
        break


    elif user_input == "1.1":
        sum1 = input("Введите числа через пробел:")
        sum1 = sum1.split()
        
        q = []
        
        for i in sum1:
            q.append(int(i))
            w = sum(h)
            print(w)

    elif user_input == "1.2":
        s = [int(x) for x in input("Введите числа через пробел").split()]

        i = 0

        summa = 0

        while i < len(s):
            summa += s[i]
            i += 1

        print(summa)

    elif user_input == "1.3":
        qwe= input("Введите числа через пробел:")
        qwe = lst.split()
        h = 0
        k = 0


        def sum1(p,k1 =0):
            k1 += float(qwe[p - 1])
            if p == 0:
                return 0
            return sum1(p - 1) + k1


        print(sum3((len(qwe))))
        
