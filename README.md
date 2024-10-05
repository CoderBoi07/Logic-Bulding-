# Blank Squre 📦
N = int(input("Enter your Number : "))
for i in range (N):
   for j in range(N):
     if (i==0 or i==n or j==0 or j==n):
        print("*",end="")
      else:
         print(" ", end="")
    print()
