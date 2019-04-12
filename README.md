"""this
is 
a 
mutli-line comment"""

#IMPORT MODULE FORMAT
from math import sqrt #imports sqrt function of math library

# DEFINING FUNCTIONS
def function_name(arguments):
  arg = arguments
  print(f"value is: {arg}")
  print("value is: {}".format(arg))
  return arg

#call function
function_name(6)

#CREATING LISTS
li = [1,2,3]
li2 = [4,5,6]

print(li+li2)
#CREATING LISTS
li = [1,2,3]
li2 = [4,5,6]
li3 = li + li2
print(li+li2)
print(f"{li} + {li2} = {li3}")
li.append(5)
print(li)
print(li.pop(3))
print(li)
li.append(5)
print(li)

#CREATING SETS
get_set = {1, 1, 2, 3, 4, 3}
print(get_set)
get_set2 = {3, 4, 5, 6}
big_set = get_set | get_set2
print(big_set)
diff_set = get_set - get_set2
print(diff_set)
big_diff_set = get_set ^ get_set2
print(big_diff_set)

#DICTIONARIES
dict1 = {'key1': 2, 'key2': 4, 'key3': 8}
print(dict1)
print(dict1['key2'])

#LOOPS
for keys in dict1:
  print(keys + " is " + str(dict1[keys]))

new_input = input("Type input: ")
print(new_input)






