# hello-world
This repository is for practicing the GitHub Flow

My name is Luis Guzman and im a sophomore at the university of albany majoring in informatics

#4-6 

for number in range(1, 21, 2):
    print(number)

#4-7

multiples_of_3 = []

for number in range(3, 31, 3):
    multiples_of_3.append(number)

for multiple in multiples_of_3:
    print(multiple)

#4-8

cubes = [number ** 3 for number in range(1,11)]

for cube in cubes:
    print(cube)

#4-9

cubes = [number ** 3 for number in range(1,11)]

print(cubes)

#Fibonacci Sequence

a = 0
print(a)

b = 1
print(b)

for i in range(18):
    c = a + b
    print(c)
    a = b
    b = c
