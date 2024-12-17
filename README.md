# Code_Challenge11.py
for r in range(5, 0, -1):
    for s in range(1, r + 1):
        print(" ", end = " ")
    for t in range(6, r, -1):
        print("*" ,end=" ")
    print()
    
max_width = 10
for i in range(max_width - 1, 0, -1):
    print(" " *(max_width -i), end="")
    print("*" *i, end="")
    print(" " *(max_width -i))
