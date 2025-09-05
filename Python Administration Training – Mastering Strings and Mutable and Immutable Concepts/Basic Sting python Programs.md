
# Basic Python Programming

## Write a Python program that demonstrates string concatenation

```
a="Manoj"
b="Savukar"

c=a+" "+b
print(c)
```

## Write a Python program to check if a string contains a specific character

```
text = "Manoj Savukar"
char_to_check = "o"

# Using 'in' operator
if char_to_check in text:
    print(f"The string contains the character '{char_to_check}'.")
else:
    print(f"The string does not contain the character '{char_to_check}'.")

```

## Write a Python program to replace a substring in a string with another string.

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

## Write a Python program to find the length of a string.

```
# Python program to find the length of a string

text = "Hello, Python!"

# Using len() function
length = len(text)

print("The string is:", text)
print("Length of the string:", length)
```

## Write a Python program that extracts a substring from a string.

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

## Write a Python program that converts a string into uppercase and lowercase.

```
# Python program to convert a string into uppercase and lowercase

text = "Hello, Python!"

# Convert to uppercase
upper_text = text.upper()

# Convert to lowercase
lower_text = text.lower()

print("Original string:", text)
print("Uppercase:", upper_text)
print("Lowercase:", lower_text)
```

## Write a Python program that checks if a string is palindrome.

```
# Python program to check if a string is palindrome

text = "madam"

# Convert to lowercase to make it case-insensitive
text = text.lower()

# Reverse the string using slicing
reversed_text = text[::-1]

if text == reversed_text:
    print(f"'{text}' is a palindrome.")
else:
    print(f"'{text}' is NOT a palindrome.")
```

## Write a Python program to compare two strings.

```
# Python program to compare two strings

str1 = "Python"
str2 = "python"

print("String 1:", str1)
print("String 2:", str2)

# Case-sensitive comparison
if str1 == str2:
    print("The strings are equal (case-sensitive).")
else:
    print("The strings are NOT equal (case-sensitive).")

# Case-insensitive comparison
if str1.lower() == str2.lower():
    print("The strings are equal (case-insensitive).")
else:
    print("The strings are NOT equal (case-insensitive).")
```

## Write a Python program that checks if a string starts with a certain letter.

```
# Python program to check if a string starts with a certain letter

text = "Python programming"
letter = "P"

print("String:", text)

# Using startswith() method
if text.startswith(letter):
    print(f"The string starts with '{letter}'.")
else:
    print(f"The string does not start with '{letter}'.")
```
