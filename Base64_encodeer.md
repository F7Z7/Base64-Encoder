# Base64 Encoder in Python

This project implements a custom Base64 encoder using Python without relying on any built-in libraries. It takes an
input string and encodes it into a Base64-encoded format, following the Base64 encoding rules.

---

## Features

- Converts any ASCII string into a Base64-encoded string.
- Implements the Base64 encoding process from scratch.
- Utilizes binary operations and padding to align with Base64 standards.

---

## How It Works

1. **ASCII to Binary Conversion**  
   Each character of the input string is converted to its ASCII value and then represented in an 8-bit binary format.

2. **Binary String Segmentation**  
   The binary string is segmented into groups of 6 bits (as required by Base64 encoding). If the length of the binary
   string is not divisible by 6, it is padded with trailing zeros.

3. **Mapping to Base64 Characters**  
   The 6-bit binary values are converted into integers and mapped to corresponding Base64 characters using a predefined
   dictionary.

4. **Padding**  
   If the encoded string's length is not a multiple of 4, padding characters (`=`) are added to meet the Base64
   standard.

---

## How to Run

### Pre-requisites

- Ensure you have Python installed (Python 3.x recommended).

## Steps
- Copy the code into a Python script file (e.g., base64_encoder.py).
- Run the script using a terminal or IDE.
- Enter the string you want to encode when prompted

## Usage
- Base64 encoding is a technique used to encode binary data into a text format.
- It is widely used in various fields to ensure that binary data can be safely transported or stored in systems that handle text.

### Input

The program prompts the user to input a string to be encoded.

### Output

The program outputs the Base64-encoded string.

---

### What i learnt from this project

- String manipulation in Python.
- Binary operations and padding techniques.
- Implementing data encoding standards from scratch.

---

## Code Example

```python
# Input: "Python"
# Output: "UHl0aG9u"
