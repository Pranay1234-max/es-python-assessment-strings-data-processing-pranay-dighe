# Python Programming Assessment: Strings & Data Processing

**Company:** Embed Square Solutions Private Limited
**Role:** Python Developer Intern
**Candidate:** Pranay Dighe
**Submission Date:** 25 September 2026

---

##  Assessment Overview

This repository contains my solution for the **Python Programming Assessment: Strings & Data Processing**.

The assessment focuses on:

* String manipulation
* String traversal and character handling
* Conditional logic applied to characters
* Clean and structured Python functions

---

##  Questions & Solutions

### 1. Reverse a String

#### Function

```python
def reverse_string(text: str) -> str:
```

#### Description

Returns the reverse of the given string.

#### Approach

The string is traversed character by character, and each character is added to the beginning of the result to construct the reversed string.

#### Example

```text
Input:  hello
Output: olleh
```

---

### 2. Count Vowels

#### Function

```python
def count_vowels(text: str) -> int:
```

#### Description

Counts the total number of vowels in the given string.

#### Vowels Considered

```text
a, e, i, o, u
```

Both uppercase and lowercase vowels are counted.

#### Approach

The function iterates through each character in the string and checks whether it is a vowel. The character is converted to lowercase to handle both uppercase and lowercase input. If the character is a vowel, the count is increased by one.

#### Example

```text
Input:  Hello World
Output: 3
```

---

##  Edge Cases

The solution handles the following cases:

* Empty strings
* Uppercase and lowercase characters
* Strings with no vowels
* Spaces
* Non-vowel characters

---

##  Testing

The functions were tested with sample inputs to verify the expected behavior.

### Reverse String

```text
Input:  hello
Output: olleh
```

### Count Vowels

```text
Input:  Hello World
Output: 3
```

---

##  Project Structure

```text
Python Solution File/
├── Reverse_String.py
└── Count_Vowels.py
```

---

##  Technology Used

* Python

---

##  Author

**Pranay Dighe**

Python Developer Intern Candidate
