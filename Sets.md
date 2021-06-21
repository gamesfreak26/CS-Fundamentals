# Sets

## What is a set?

A set is a collection of unique items.  

```A = { 1, 3, 5 }``` is a set

```B = { 1, 3, 3, 7 }``` is not a set

## What is a domain?

A domain is the larger set that the set is from.  

So, if the domain is the string  ```"Tharanga"```, the set is ```{ "t", "h", "a", "r", "n", "g" }```

### Common Domains

Integers 
```ℤ = { ..., -3, -2, -1, 0, 1, 2, 3, ... }``` ( -∞ to +∞ )

Natural
```N = { 1, 2, 3, ... }``` ( All numbers from 1 to ∞ )

## Symbols

Symbol | Description | Additional Note
--- | --- | ---
∪ | Union | OR
∩ | Intersection | AND
' | Complement | NOT
\- | Set Difference | 
⊕ | Symmetric Difference | XOR
⊂ | Proper Subset
⊆ | Subset
⊇ | Proper Superset
⊃ | Superset
∈ | Element of 
∉ | Not an element of

These will be explained below. 


## Definitions

- Domain - The larger collection that the set is from.  
- Element - An item in the set
- Subset - One set is contained within another set.
- Proper subset - one set is contained within another set and does not contain all elements of its superset (they are not equal)
- Superset - one set contains another set 
- Proper Superset - one set contains another set and contains more than that subset (they are not equal)

## Combining Sets - Union, ∪

Contains all elements that appear in either set (OR)

A = { 1, 2, 3, 4 }

B = { 3, 4, 5, 6 }

A ∪ B = { 1, 2, 3, 4, 5, 6 }

## Combining Sets - Intersection, ∩

Contains the elements that appear in both sets (AND)

A = { 1, 2, 3, 4 }

A = { 3, 4, 5, 6 }

A ∩ B = { 3, 4 }

## Combining Sets - Complement, ' 

Elements in the domain that are in the domain and not in the set (NOT)

Domain: All natural numbers < 10

A = { 1, 2, 3, 4 }

B = { 3, 4, 5, 6 }

( A ∪ B)' = { 7, 8, 9 }

A' = { 5, 6, 7, 8, 9 }

B' = { 1, 2, 7, 8, 9 }

## Combining Sets - Difference, A - B  or A \ B

All elements in one set that are not in another set

A = { 1, 2, 3, 4 }

B = { 3, 4, 5, 6 }

A - B = { 1, 2 }

B - A = { 5, 6 }

## Combining Sets - Symmetric Differience (XOR), ⊕

All elements that are in either set but not in both (exclusive or)

A = { 1, 2, 3, 4 }

B = { 3, 4, 5, 6 }

A ⊕ B = { 1, 2, 5, 6 }

A ⊕ B = ( A - B ) U ( B - A )

Can also be expressed as: `A ⊕ B = ( A U B ) - ( A ∩ B)`

## Examples

Example 1

`A = { x | x ∈ N, x < 5 }`   --> x such that x is an element of N and x < 5

    = `{ 1, 2, 3, 4 }`


Example 2

`A = { x | x ∈ Z, -3 < x < 3 }` = `{ -2, -1, 0, 1, 2 }`

Example 3

`A = { 1, 2, 3 }`          

`B = { x | x ∈ N, x < 10, x ∉ A }`

`B = { 4, 5, 6, 7, 8, 9 }`
