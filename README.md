# CIS567-Integrated-lab-1
Lab: Output range with increment of 5

x = int(input())
y = int(input))
if y >= x:
  for i in range (x, y + 1, 5,):
    print(i, end=' ')
  print()
else:
  print('Second integer can\'t be less than the first.')
