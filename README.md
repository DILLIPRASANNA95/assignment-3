# assignment-3
myList = [1, 2, 3, 4, 5, 6, 7, 8, 9]
print("The given list is:")
print(myList)
list_length = len(myList)
sumOfElements = 0
count = 0
while count < list_length:
    sumOfElements = sumOfElements + myList[count]
    count = count + 1
    print("Sum of all the elements in the list is:", sumOfElements)
    
