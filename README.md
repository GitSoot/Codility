# Codility Solution

- The function takes two string parameters, str1 and str2, and return the merged string. 

- It first loops through the characters of str1 backwards and checks if the suffix matches the beginning of str2.

- If there is a match, it concatenates str1 and the part of str2 that comes after the suffix.

- If there is no match, it concatenates the two strings as is.
