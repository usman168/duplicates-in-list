# Find duplicates in 2 lists

def duplicates():
  a= [1, 2, 3, 4, 5]
  b = [2, 4, 6, 5, 3]
  return[i for i in a if i in b]

print(duplicates())
