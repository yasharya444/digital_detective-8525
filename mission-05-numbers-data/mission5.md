
# Task 5.1 - Convert Numbers by Hand

### 1. Decimal 13 to Binary
13 / 2 = 6, 
- r = 1
- 6 / 2 = 3,
- r = 0
- 3 / 2 = 1, 
- r = 1
- 1 / 2 = 0, 
- r = 1

Answer: 1101

### 2. Decimal 25 to Binary
25 / 2 = 12, 
- r = 1
- 12 / 2 = 6, 
- r = 0
- 6 / 2 = 3, 
- r = 0
- 3 / 2 = 1, 
- r = 1
- 1 / 2 = 0, 
- r = 1

Answer: 11001

### 3. Binary 1010 to Decimal
= (1 × 2** 3) + (0 × 2** 2) + (1 × 2) + (0 × 2**0)
= 8 + 0 + 2 + 0

Answer: 10

### 4. Binary 1101 to Decimal
= (1 × 2** 3) + (1 × 2** 2) + (0 × 2) + (1 × 2** 0)
= 8 + 4 + 0 + 1

Answer: 13

### 5. Hexadecimal A to Decimal
A = 10

Answer: 10

### 6. Hexadecimal 1F to Decimal
= (1 × 16** 1) + (15 × 16** 0)
= 16 + 15

Answer: 31

### 7. Binary 1111 to Hexadecimal
- 1111 (Binary) = 15 (Decimal)
- 15 (Decimal) = F (Hexadecimal)

Answer: F


# Task 5.2 - Verify Using Python

| Conversion | Python Expression | Result | Match |
|---|---|---|---|
| Decimal 13 to binary | bin(13) | 0b1101| Yes |
| Decimal 25 to binary | bin(25) | 0b11001 | Yes |
| Binary 1010 to decimal | int('1010', 2) | 10 | Yes |
| Binary 1101 to decimal | int('1101', 2) | 13 | Yes |
| Hexadecimal A to decimal | int('A', 16) | 10 | Yes |
| Hexadecimal 1F to decimal | int('1F', 16) | 31 | Yes |
| Binary 1111 to hexadecimal | hex(int('1111', 2)) | 0xf | Yes |


# Task 5.3 - Build a small number converter
|Test number|Binary output|Hexadecimal output|
|:---:|:---:|:---:|
|25|0b11001|0x19|
|67|0b1000011|0x43|
|22|0b10110|0x16|

- The bin() function converts an integer (decimal number) into its binary representation
- The hex() function converts an integer (decimal number) into its hexadecimal representation.
- int() can convert a number represented in another base into a decimal integer.

# Task 5.4 - How is text stored 

### 1. ASCII Decimal Codes
- Uppercase A = 65
- Lowercase a = 97

### 2. Why does a computer need an encoding standard?
Computers store information in binary form (0s and 1s). Encoding standards assign numerical values to characters so that text can be stored, processed and displayed correctly.

### 3. Example of a character not in basic ASCII
The Indian Rupee symbol (₹) is not included in basic ASCII. It can be represented using Unicode encoding such as UTF-8.