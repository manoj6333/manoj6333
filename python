num = int(input("Enter number: "))
digit = int(input("Enter a Digit: "))

temp = num
rev = 0
count = 0  # Initialize count

while num != 0:
    rem = num % 10
    rev = rev * 10 + rem
    num = num // 10
    if rem == digit:
        count += 1

if temp == rev:
    print("The number is a palindrome!")
else:
    print("The number isn't a palindrome!")

print("{} occurred {} times in {}".format(digit, count, temp))
