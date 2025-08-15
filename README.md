import random
import string
length = int(input("Enter password length: "))
password = ""
for _ in range(length):
    password += random.choice(string.ascii_letters + string.digits)
print("Generated Password:", password)
