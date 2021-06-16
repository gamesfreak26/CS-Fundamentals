# Boolean Algebra

- Branch of mathematics that involves boolean values and operations on boolean values.
- Used to break down complex problems.
- Boolean Values may be expressed as TRUE or FALSE, or 1 and 0, respectively.

### Legend

T | F
--- | ---
1 | 0

_______

# NOT relation and operators

Unary boolean relation (it's unary as it is evaluated on one expression instead of two)

Gives the opposite of the value given

- NOT true = false
- NOT false = true

### Symbols that denote NOT

- ¬
- ˜
- !

_______

# AND relation and operators

Both values must be true for AND to evaluate to true

### AND TABLE

Note: In the videos, the table is upside down.

A | B | A ∧ B
--- | --- | ---
F | F | F
F | T | F
T | F | F
T | T | T

In binary

A | B | A ∧ B
--- | --- | ---
0 | 0 | 0
0 | 1 | 0
1 | 0 | 0
1 | 1 | 1

### Symbols that denote AND

- ∧
- ·
- &

_______

# OR relation and operators

The only time an OR is false is when both values are false

### OR TABLE

Note: In the videos, the table is upside down.

A | B | A ∨ B
--- | --- | ---
F | F | F
F | T | T
T | F | T
T | T | T

A | B | A ∨ B
--- | --- | ---
0 | 0 | 0
0 | 1 | 1
1 | 0 | 1
1 | 1 | 1

### Symbols that denote OR

- ∨
- \+
- ∥

_______

# XOR relation and operators

Exclusive OR.  Both values can't be ( TRUE and TRUE ) or ( FALSE and FALSE ) at the same time.

Another way of writing this is: A ⊕ B = ( A ∨ B ) ∧ !( A ∧ B )

### XOR TABLE

Note: In the videos, the table is upside down.

A | B | A ⊕ B
--- | --- | ---
F | F | F
F | T | T
T | F | T
T | T | F

A | B | A ⊕ B
--- | --- | ---
0 | 0 | 0
0 | 1 | 0
1 | 0 | 0
1 | 1 | 1

### Symbols that denote XOR

- ⊕
- ⊻

_______

# Implication 

If p is TRUE, then q is TRUE.  It is **only false** when p is true and q is false.

p | q | p → q
--- | --- | ---
F | F | T
F | T | T
T | F | F
T | T | T

### Symbols that denote IMPLICATION
- ⇒
- →

# Equivalence 

q is true if and only if p is true.  Opposite of a Exclusive OR (XOR).  p and q have to be the same. 

p | q | p ↔ q
--- | --- | ---
F | F | T
F | T | F
T | F | F
T | T | T

### Symbols that denote EQUIVALENCE

- ⇔
- ≡
- ↔

_______

# Bitwise Operations

We can apply logical operations to a series of bits (binary numbers)

1100110 AND 111010

![Screenshot 2021-06-16 085342](https://user-images.githubusercontent.com/3919875/122133601-63c62d80-ce80-11eb-95a7-303b3846a74b.png)

1100110 OR 111010

![Screenshot 2021-06-16 085342](https://user-images.githubusercontent.com/3919875/122133733-9ec86100-ce80-11eb-889e-31fea36e83a6.png)

1100110 XOR 111010

![Screenshot 2021-06-16 085342](https://user-images.githubusercontent.com/3919875/122133858-d9ca9480-ce80-11eb-8fbb-209c5f890a44.png)

32 XOR 17

1. Convert to Binary

![Screenshot 2021-06-16 093815](https://user-images.githubusercontent.com/3919875/122137264-932c6880-ce87-11eb-97bf-e510779973c4.png)


![Screenshot 2021-06-16 093126](https://user-images.githubusercontent.com/3919875/122136374-b6eeaf00-ce85-11eb-90d0-4ed38cbcd379.png)


2. XOR

![Screenshot 2021-06-16 095036](https://user-images.githubusercontent.com/3919875/122137621-66c51c00-ce88-11eb-9d4c-4a237f1f7d16.png)

3. Convert back to Decimal

![Screenshot 2021-06-16 095338](https://user-images.githubusercontent.com/3919875/122137782-c6bbc280-ce88-11eb-86ac-0efc8ec6047c.png)

_______

# Logic Statements - Writing in symbolic form

Syntax used to express logic statements with a combination of symbols and logical operators.  

- Symbols represent statements that evaluate to TRUE
- Operators used include AND, OR, NOT, XOR (and any symbols we use to represent those)
- Not a if / else statement - it's more general

d: Dinner includes soup

s: Dinner includes salad

v: Dinner includes vegetables

Dinner consists of soup and sald or vegetables

d ∧ (s ∨ v)

Dinner consists of soup or salad and vegetables

d ∨ (s ∧ v)
