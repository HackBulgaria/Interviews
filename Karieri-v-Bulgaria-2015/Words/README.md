# Words

Lets play a game!

You are given a rectangular table filled with characters and a `word`.

Your task is to count the occurrences of the `word` in the table.

**The word can be found horizontaly, vertically and across both left to right and right to left.**

## For example

find the word `ivan` in the table:

| i    | v     | a     | n     |
|---   |---    |---    |---    |
| e    | **v** | **n** | h     |
| i    | n     | **a** | v     |
| m    | v     | **v** | **n** |
| q    | r     | **i** | t     |

Result:

```
3
```

## The problem

You are given the rectangular matrix and a `word`. You should output the number of ccurrences.

* How are you going to solve that problem in an OOP language?
* How are you going to model everything?

Give your best!

## Examples

All inputs are given in the form:

```
on-the-first-line-is-the-word
n m, where n is number of rows, m number of cols
on the next n lies, the matrix
```

### Example 1

```
ivan
5 4
i v a n
e v n h
i n a v
m v v n
q r i t
```

Should print:

```
3
```

### Example 2

```
actually
8 15
i v a n q h r e z g t z o y m
e v n h t r x e k y d a i l c
i a c t u a l l y m c x r l e
m v c n p u a m n t l u e a a
q r i t w e a q u p r x t u z
p e a c t u a l l y w p y t m
o y h t r e l u f p q n z c s
p a c t u a l l y u r e q a r
```

Should print:

```
4
```

### Example 3

```
madam
8 12
z v a n q h r e z g t z
e v m h t r x e k y m a
i a c a u a l l y a c x
m v c n d u a m d t l u
q t i t w a a a u p r x
p e m a d a m l l y w p
o y h t e e l u f p q n
p a c t u a l l y u r e
```

Should print:

```
3
```

Note: this should print 3, not 6
