# hw3 Логические и условные операторы
#Задание 
Напишите программу для кинотеатра. Пользователь вводит возраст и наличие сопровождающего. Если возраст меньше 12 лет, программа выводит "Билет бесплатный".
Если возраст от 12 до 18 лет и есть сопровождающий, программа выводит "Билет со скидкой". Во всех остальных случаях программа выводит "Полная стоимость билета".

age = int(input("Введите возраст: "))

accompanied = input(" Есть сопровождающий (да\нет): ")

if age < 12:
   print("Билет бесплатный")

elif age >= 12 and age <= 18 and accompanied =="да":
   print("Билет со скидкой")

else:
   print("Полная стоимость билетов")


