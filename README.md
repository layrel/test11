# На вход подается 1 строка без пробелов. По данной строке определите, является ли она палиндромом (то есть, можно ли прочесть ее наоборот, как, например, слово "шалаш"). Необходимо вывести ”yes”, если строка является палиндромом, и “no” в противном случае.
# Решение:
slovo = str(input())
a = slovo[::-1]
if slovo == a:
 print("yes")
else:
 print("no")
