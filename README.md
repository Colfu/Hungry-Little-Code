# Hungry-Little-Code
# The first project of my own

# It started off with copying some code to work out the largest number from a given list. It made sense.

largest_number = 0
for thing in [9, 41, 12, 3, 74, 15]:
  if thing > largest_number:
      largest_number = thing
print('Largest number is', largest_number, '. Thank you.')

# This gives out: ‘Largest Number is 74 . Thank you!’ Except that extra space after the 74 annoyed me, so google told me to add ‘sep = ‘ in there, which worked, but I have no idea how, so added it to my list of questions to come back to.

# I then decided I would ‘quickly’ try making it where the user input the numbers for the list themselves, rather than having them already specified in the code.

# And then it spiraled from there ...
