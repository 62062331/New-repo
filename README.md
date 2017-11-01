#used method:
#1. Lists
#2. More conditionals (if statements)

list1 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14 ,15]

check = int(input("give me a number: " ))

new_list = []

for i in list1:

	if i % 4 == 0:

 		new_list.append(i)
print(new_list)

