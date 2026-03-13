arr = [1, 2, 0, 4, 3, 0, 5, 0]

pos = 0

for i in range(len(arr)):
    if arr[i] != 0:
        arr[pos], arr[i] = arr[i], arr[pos]
        pos += 1

print(arr)# Data-structure27
Data structur 
