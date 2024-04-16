# Demo3
x = 64 < 83
print(x)
x = 73 < 45
print(x)
x = 8.3 < 43
print(x)
x = 'Sample' < 'sample'
print(x)
print((22, 25, 34) < (32, 34, 46, 76))

print(48 > 64)
print(33 > 21)

print(64 == 64)
print(43 == 42)

a = "34"
print(a + " is my favorite number")

# циклы
number = 43
if number % 3 == 0:
 print ("This number is divided by 3")
else:
 print ("This number is not divisible by 3")

number = 40
if number % 4 == 0:
 print ("This number is divided by 4")
else:
 print ("This number is not divisible by 4")


sample = 45
if sample % 3 == 0:
     print("This number is divisible by 3")
elif sample % 4 == 0:
     print("This number is divisible by 4")
else:
     print("This number is not divisible by 3 and 4")

n = 4
i = 1
while i <= n:
    if i % 2 == 0:
        print(i, "is divided by 2")
    if i % 3 == 0:
        print(i, "is divisible by 3")
        break
    i = i + 1

for var in 'computer':
    if var == 'r':
        continue
    print('Letter now:', var)

