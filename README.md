# Delete-from-list-python
numbers = [3, 4, 1, 9, 6, 2, 8]
print("Original list:", numbers)
x = int(input("Enter the position of the element to be deleted: "))
if 0 <= x < len(numbers):
    numbers.pop(x)
    print("Updated list:", numbers)
else:
    print("Invalid position! Please enter a position between 0 and", len(numbers)-1)
    OUTPUT:
    Original list: [3, 4, 1, 9, 6, 2, 8]
Enter the position of the element to be deleted: 5
Updated list: [3, 4, 1, 9, 6, 8]

