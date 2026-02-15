# Calculations Priorities — Summary

## 1) Operator Precedence
- Determines **order in which operations are executed** in an expression.
- Higher precedence operators are evaluated **before** lower precedence ones.

## 2) Common Precedence Rules
1. **Parentheses `()`** — highest priority, expressions inside are calculated first.
2. **Exponents / Powers `^`** — calculated after parentheses.
3. **Multiplication `*` and Division `/`** — same level, evaluated **left to right**.
4. **Addition `+` and Subtraction `-`** — same level, evaluated **left to right**.
5. **Comparison Operators `<, >, <=, >=, ==, !=`** — after arithmetic operations.
6. **Logical NOT `!`** — evaluated before AND/OR.
7. **Logical AND `&&`** — evaluated before OR.
8. **Logical OR `||`** — lowest priority.

## 3) Examples
- `3 + 5 * 2` → 3 + (5*2) = 13  
- `(3 + 5) * 2` → (3+5) * 2 = 16  
- `10 - 4 / 2` → 10 - (4/2) = 8  
- `!(5 > 3) || (2 < 4)` → !True || True → False || True → True

## 4) Tips
- Use **parentheses** to clarify and control calculation order.  
- Remember **left-to-right** evaluation for operators of same precedence.  
- Logical operations follow **arithmetic operations** precedence.

---


