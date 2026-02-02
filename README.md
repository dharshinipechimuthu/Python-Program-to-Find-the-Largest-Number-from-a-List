# Python-Program-to-Find-the-Largest-Number-from-a-List
n = int(input("Enter the number of elements: "))

largest = -99999999999

for i in range(1, n + 1):
    a = int(input(f"Enter {i}th number: "))
    if a > largest:
        largest = a

print("Largest number is:", largest)

Output:
Enter the number of elements: 5
Enter 1th number: 10
Enter 2th number: 45
Enter 3th number: 23
Enter 4th number: 89
Enter 5th number: 12
Largest number is: 89
