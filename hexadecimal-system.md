# Hexadecimal System in Computers

## What is the Hexadecimal System?
The hexadecimal system (Hex) is a number system with base 16. It uses 16 symbols to represent values:

0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

Where:
- A = 10
- B = 11
- C = 12
- D = 13
- E = 14
- F = 15

Hexadecimal is widely used in computers because it provides a compact and human-readable way to represent binary data.

---

## Why Do Computers Use Hexadecimal?
- Easier to read and write than long binary numbers.
- More compact representation of data.
- Commonly used in programming, memory addresses, and debugging.
- Each hexadecimal digit represents exactly 4 binary bits.

---

## Relationship Between Binary and Hexadecimal
Every hexadecimal digit corresponds to 4 binary bits.

Examples:
- Binary 0000 = Hex 0
- Binary 0001 = Hex 1
- Binary 1010 = Hex A
- Binary 1111 = Hex F

Example conversion:
- Binary: 11010110  
- Group into 4 bits: 1101 0110  
- Hex: D6  

---

## Hexadecimal Number Examples
- Decimal 10 = Hex A
- Decimal 15 = Hex F
- Decimal 16 = Hex 10
- Decimal 255 = Hex FF
- Decimal 256 = Hex 100

---

## Where is Hexadecimal Used?
- Memory addresses (e.g., 0x7FFE)
- Color codes in web design (e.g., #FF5733)
- Debugging and reverse engineering
- Malware analysis
- Assembly language and low-level programming

---

## Importance in Cybersecurity
Understanding hexadecimal helps in:
- Analyzing memory dumps
- Reverse engineering binaries
- Reading network packet data
- Malware analysis
- Digital forensics

# Hexadecimal System and Conversions in Computers

## What is Hexadecimal?
- Hexadecimal (Hex) is a base-16 number system.
- Symbols: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F
- Each Hex digit represents 4 binary bits.
- 1 byte (8 bits) = 2 Hex digits.

---

## Hex ↔ Decimal Conversion

### Hex → Decimal
1. Multiply each digit by 16^position (starting from right, position = 0)
2. Sum the results

**Example:** A5 (Hex) → Decimal  

### Decimal → Hex
1. Divide the decimal number by 16 repeatedly
2. Write remainders from last to first

**Example:** 165 → Hex  

---

## Hex ↔ Binary Conversion

### Hex → Binary
1. Convert each Hex digit to 4-bit binary

**Example:** A5 → Binary  

### Binary → Hex
1. Group binary digits into 4-bit groups from right
2. Convert each group to Hex

**Example:** 10100101 → Hex  

---

## Decimal ↔ Binary Conversion

### Decimal → Binary
1. Divide the decimal number by 2 repeatedly
2. Write remainders from last to first

**Example:** 165 → Binary  

### Binary → Decimal
1. Multiply each bit by 2^position (starting from right, position = 0)
2. Sum the results

**Example:** 10100101 → Decimal  
