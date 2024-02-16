# hallow-triangle
n=int(input())
for i in range(n):
  for j in range(n):
    if i>=j and i==j or i==0 or j==(n-1):
     print(f"{i}{j}",end=" ")
    else:
      print(" ",end=" ")
  print()


#using '*' pattern
n=int(input())
for i in range(n):
  for j in range(n):
    if i>=j and i==j or i==0 or j==(n-1):
     print(f"*",end=" ")
    else:
       print(" ",end=" ")
  print()




  
