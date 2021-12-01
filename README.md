import math

def divisor():
    numb = int(input("Enter number: "))
    divisor = []
    for i in range(1, numb + 1):
        if (numb % i == 0):
            divisor.append(i)

    print("\n")

    dalijums = sum(divisor)
    print("All your divisors : ", divisor)
    print("Sum of all divisors:\n")
    print(dalijums)


if __name__ == '__main__':
    divisor()
