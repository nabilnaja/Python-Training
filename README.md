# Python-Training
Python training

## Numeric type
Integers (unlimited size) : 1234, −24, 0, 99999999999999 

Floating-point numbers : 1.23, 1., 3.14e-10, 4E210, 4.0e+210

Octal, hex, and binary literals : 0o177, 0x9ff, 0b101010
 
Complex number literals : 3+4j, 3.0+4.0j, 3J

Sets: 3.X construction forms : set('spam'), {1, 2, 3, 4}

Decimal : ('1.0')

Fraction : Fraction(1, 3)

Boolean type and constants : bool(X), True, False

### Numeric built-in function

hex(I), oct(I), and bin(I) : convert an integer to its representation string in these three bases -> int('64'), int('100', 8), int('40', 16), int('1000000', 2).

int(str, base) converts a runtime string to an integer per a given base.

is_integer : test if the number is an integer.

bit_length : gives the number of bits necessary to represent an integer.

Truncates float to integer : int(3.1415)

Converts integer to float : float(3)

Rounds and drops decimal digits : round() it still produces a floating-point number in memory.

## str and repr Display Formats

echoes, as-code form : repr('spam') -> "'spam'" 

print, user-friendly form: str('spam') -> 'spam'

## Random

random.random()

random.randint(1, 10)

random.choice([[...])

random.shuffle([[...])

## File type

for char in open('test.txt').**read()**: processes each character at once, but it loads the file into memory all at
once. 
for line in open('test.txt'): Use iterators



