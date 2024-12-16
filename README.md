# Creating a list
my_list = [1, 2, 3, 4, 5]
print("Original List:", my_list)

my_list.append(6)
print("List after adding an element:", my_list)

my_list.remove(3)
print("List after removing an element:", my_list)

my_list[0] = 10
print("List after modifying an element:", my_list)

my_dict = {'name': 'Anya', 'age': 18, 'city': 'California'}
print("\nOriginal Dictionary:", my_dict)

my_dict['Gender'] = 'Female'
print("Dictionary after adding a key-value pair:", my_dict)

del my_dict['age']
print("Dictionary after removing a key-value pair:", my_dict)

my_dict['city'] = 'California'
print("Dictionary after modifying a value:", my_dict)

my_set = {1, 2, 3}
print("\nOriginal Set:", my_set)

my_set.add(4)
print("Set after adding an element:", my_set)

my_set.discard(2)
print("Set after removing an element:", my_set)

my_set.add(3)
print("Set after attempting to add a duplicate element:", my_set)

print("\nFinal List:", my_list)
print("Final Dictionary:", my_dict)
print("Final Set:", my_set)
