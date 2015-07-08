# String Permutations

[You can solve that problem in the arena](https://arena.hackbulgaria.com)

In a language of your choice, implement a problem that:

* On the first line of the input, reads one string - `s`
* After this, reads an integer `n`
* On the next `n` lines, reads `n` more strings.

The program should output the number of strings, that are a permutation of the characters in the string `s`.

Restrictions:

* `1 <= n <= 100`
* The length of each string is between 1 and 100

## Examples

Input:

```
baba
3
abba
abab
bbbb
```

Output:

Here, the permutations of `baba` are `abba` and `abab`.

```
2
```

---

Input:

```
hack bulgaria
2
ha ckbulgaria
hackbulgaria 
```

Output:

```
2
```

The last string from the input has a trailing whitespace.
