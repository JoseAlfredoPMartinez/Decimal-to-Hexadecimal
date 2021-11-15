numch = ""
n=int(input("Decimal number: "))
deci = [10, 11, 12, 13, 14, 15 ]
hexa = ["a", "b", "c", "d", "e", "f"]

if n <= 0:
    numch = "0"
else:
    while n != 0:
        x = n % 16
        n = int(n / 16)

        if x < 10:
            numh = str(x)
        else:
            for i in range(7):
              if x == deci[i-1]:
                numh = hexa[i-1]

        numch = numh + numch

print("in hexadecimal:",numch)
