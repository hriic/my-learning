# Octal System in Computers

## What is the Octal System?
The octal system is a number system with base 8. It uses 8 digits to represent values:

0, 1, 2, 3, 4, 5, 6, 7

Octal is mainly used in computing as a compact way to represent binary numbers.

---

## Why Do Computers Use Octal?
- Easier to read and write than long binary numbers.
- Each octal digit represents exactly 3 binary bits.
- Used in early computing systems and some modern applications.

---

## Relationship Between Binary and Octal
Each octal digit corresponds to 3 binary bits.

| Binary | Octal |
|--------|--------|
| 000    | 0      |
| 001    | 1      |
| 010    | 2      |
| 011    | 3      |
| 100    | 4      |
| 101    | 5      |
| 110    | 6      |
| 111    | 7      |

---

## Octal Conversions

### Octal → Decimal
Multiply each digit by 8^position (position starts from 0 at the right).

**Example:** 345 (Octal) → Decimal  

---

### Decimal → Octal
Divide the decimal number by 8 repeatedly and write remainders from last to first.

**Example:** 229 → Octal  

---

### Octal → Binary
Convert each octal digit to 3-bit binary.

**Example:** 345 → Binary  

---

### Binary → Octal
Group binary digits into 3-bit groups from right and convert each group to octal.

**Example:** 011100101 → Octal  

---

## Where is Octal Used?
- File permissions in Linux (e.g., chmod 755)
- Early computer systems
- Low-level programming
- Digital electronics

---

## Importance in Cybersecurity
Understanding octal helps in:
- Linux file permissions
- System administration
- Security configuration
- Access control management
