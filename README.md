# Create an empty list
my_list = []

# Append elements 10, 20, 30, and 40 to the list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert the value 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend the list with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element (index -1) from the list
my_list.pop()

# Sort the list in ascending order
my_list.sort()

# Find and print the index of the value 30 in the list
index_of_30 = my_list.index(30)

print(f"The index of the value 30 is: {index_of_30}")
