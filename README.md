# My-first-min-project
i just made this to help my self there is something i need to go over to remember 

from typing import final

while True:
    name = input("Enter your name :")
    if name.strip() == "":
        continue

    else:
        break
age = int(input("Enter your age: "))
if age >= 18:
    print("You are old enough to keep going")
else:
    print("You are not old enough to go through")

print("hello" + " " + name + " " + "you are" + " "+ str(age) + " " + "Years old")
