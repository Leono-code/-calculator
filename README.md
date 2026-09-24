zmienna1 = int(input("First number: "))
sign = input("sign: ")
zmienna2 = int(input("Second number: "))
zmienna3 = "I don't understand"
if sign == "+":
    zmienna3 = zmienna1 + zmienna2
if sign == "-":
    zmienna3 = zmienna1 - zmienna2
if sign == "*":
    zmienna3 = zmienna1 * zmienna2
if sign == "/":
    zmienna3 = zmienna1 / zmienna2
if sign == "%":
    zmienna3 = zmienna3 % zmienna2
print(zmienna3)
