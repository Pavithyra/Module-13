# Exp.No:31  
## IMPLEMENTATION OF STACK

---

### AIM  
To write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

```
# REGNO:-212222060174
# name:-Pavithra.S
stack = []
for i in range(5):
    s=input()
    stack.append(s)
print("Stack before elements are popped")
print(stack)
stack.pop()
stack.pop()
print("\nStack after elements are popped:")
print(stack)

```

### OUTPUT

<img width="768" height="370" alt="image" src="https://github.com/user-attachments/assets/453e5304-c6e6-4dc2-a41e-cfbf2379b4b3" />

### RESULT

Thus a Python program to implement a stack using a list and its built-in methods (append(), pop()) has been executed succesfully.


<img width="768" height="370" alt="image" src="https://github.com/user-attachments/assets/abad6552-f03b-4e93-82dd-3f76d6745f48" />
