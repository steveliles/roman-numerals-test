# Technical Test - React Developer

## Test Part I

The numeric system represented by Roman numerals originated in ancient Rome and remained the usual way of writing numbers throughout Europe well into the Late Middle Ages. Numbers in this system are represented by combinations of letters from the Latin alphabet. Roman numerals, as used today, are based on seven symbols:

| Symbol | I   | V  | X   | L   | C   | D   | M    |
| -------| --- |--- | --- | --- | --- | --- | ---- |
| Value  | 1   | 5  | 10  | 50  | 100 | 500 | 1000 |

In its simplest form, the numbers 1 to 10 are expressed as follows:

I, II, III, IIII, V, VI, VII, VIII, VIIII, X

Some examples of larger numbers include:

12   as XII
25   as XXV
140  as CXXXX
1954 as MDCCCCLIIII
1990 as MDCCCCLXXXX
2014 as MMXIIII
2017 as MMXVII

Using node.js, Create a javascript function `toSimpleRoman` that can convert from our modern numbering system (positional Arabic numerals) to Roman numerals, e.g.

```
> toSimpleRoman(9)
> VIIII
>
> toSimpleRoman(12)
> XII
>
> toSimpleRoman(1990)
> MDCCCCLXXXX
>
> toSimpleRoman(140)
> CXXXX
```

## Test Part II

In a few specific cases, to avoid confusing and hard to read numbers with four characters repeated in succession (such as IIII or XXXX), subtractive notation is used, as in this table:

| Number   | 4   | 9   | 40  | 90  | 400 | 900 |
| -------- | --- | --- | --- | --- | --- | --- |
| Notation | IV  | IX  | XL  | XC  | CD  | CM  |

The numbers 1 to 10 are thus more commonly expressed in Roman numerals as follows:

I, II, III, IV, V, VI, VII, VIII, IX, X.

Some examples of the modern use of Roman numerals include:

| Positional Arabic | Roman  |
| ----------------- | ------ |
| 12                | XII    |
| 25                | XXV    |
| 140               | CXL    |
| 1954              | MCMLIV |
| 1990              | MCMXC  |
| 2014              | MMXIV  |
| 2017              | MMXVII |

Using node.js, Create a javascript function `toCompactRoman` that converts from our modern numbering system to Roman numerals, using the more compact subtractive notation as described earlier in this section, e.g.:

```
> toCompactRoman(9)
> IX
>
> toCompactRoman(12)
> XII
>
> toCompactRoman(1990)
> MCMXC
>
> toCompactRoman(140)
> CXL
```
