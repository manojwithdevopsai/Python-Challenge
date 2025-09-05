# Write a Python program that demonstrates string concatenation

```
a="Manoj"
b="Savukar"

c=a+" "+b
print(c)
```

# Write a Python program to check if a string contains a specific character

```
text = "Manoj Savukar"
char_to_check = "o"

# Using 'in' operator
if char_to_check in text:
    print(f"The string contains the character '{char_to_check}'.")
else:
    print(f"The string does not contain the character '{char_to_check}'.")

```

# Write a Python program to replace a substring in a string with another string.

```
# Python program to replace a substring in a string

text = "I enjoy learning Java programming."
old_substring = "Python"
new_substring = "Java"

# Replace the substring
updated_text = text.replace(old_substring, new_substring)

# Print results
print("Original string:", text)
print("Updated string:", updated_text)
```

# Write a Python program to find the length of a string.

```
# Python program to find the length of a string

text = "Hello, Python!"

# Using len() function
length = len(text)

print("The string is:", text)
print("Length of the string:", length)
```

# Write a Python program that extracts a substring from a string.

```
# Python program to extract a substring from a string

text = "Hello Python!"

# Extract substring from index 6 to 11 (Python)
substring = text[7:13]

print("Original string:", text)
print("Extracted substring:", substring)


#Substracting sting with word level
text = "Hello Python!"

#Extract substring from index 6 to 11 (Python)
word= text.split()
substract_word = word[0]

print("Extracted substring:", substract_word)
```
