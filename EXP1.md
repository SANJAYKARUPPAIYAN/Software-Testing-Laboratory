# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                           
### REGISTER NUMBER : 212222040146

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

### i.)do…while: 

```
def display():
     start=input("Enter a positive value for START: ")
      end=input("Enter a positive value for END: ")
      if start.isnumeric() and end.isnumeric():
        while True:
            start=int(start)
            end=int(end)
            print(start,end=‘ ‘)
            if start<end:
                start+=1
            else:
                break
      else:
        print("Enter a valid positive number.") 
  display() 
```

### ii.) while…do 

```
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ")
if start.isnumeric() and end.isnumeric():
     start=int(start)
     end=int(end)
     while start<end:
          print(start)
          start+=1
else:
   print("Enter a valid positive number.")

```

### iii.) switch 

```
def switch():
    switcher={
 0:"even",
  1:"odd"
}
n=input('Enter a value for N: ') try:
  n=int(n)
  print(switcher[n%2])
except ValueError:
   print("Enter a valid number.")
switch() 

```

### iv.) if else

```
def compare():
  a=input("Enter a value for A: ")
  b=input("Enter a value for B: ")
  try:
     a=int(a)
     b=int(b)
     if a>b:
        print("A is greater than")
     elif a<b:
        print("B is greater than")
     else:
        print("A is equal to B")
  except ValueError:
        print(“Enter a valid number.”) 

```

### v.) for

```
def iterate():
    string=input("Enter a string: ") for
    i in string:
       print(ord(i),end=" ")
iterate() 
```


### Output:

### i.)do…while: 

![do while](https://github.com/user-attachments/assets/2e42a1bb-cba9-4ee6-867f-e9ecc1c12b45)

### ii.) while…do 

![do while](https://github.com/user-attachments/assets/35b5e234-f3cf-4073-8a38-9155638a1e3c)

### iii.) switch 

![switch](https://github.com/user-attachments/assets/b60fe3fd-6839-4e83-ab50-d472be6188c9)

### iv.) if else

![if else](https://github.com/user-attachments/assets/25b35f83-b728-484f-8c74-df392115b67a)

### v.) for 

![for loop](https://github.com/user-attachments/assets/d7e05552-baac-4954-ba91-df8bffd67826)

### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.



