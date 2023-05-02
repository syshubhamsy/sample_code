def count_frequency(arr):
    freq = {}
    for i in arr:
        if i in freq:
            freq[i] += 1
        else:
            freq[i] = 1
    return freq

# Prompt the user to enter an array
arr = input("Enter an array of elements separated by spaces: ").split()

# Find the frequency of each element in the array
freq = count_frequency(arr)
print(freq)