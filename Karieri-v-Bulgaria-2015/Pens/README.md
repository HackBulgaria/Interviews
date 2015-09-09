# Pens

One of the main reasons people go to career events is to gather as many pens as they can. One career event can provide you with enough pens for the rest of the year.

It's been a long day and you have managed to collect a lot of pens.

But there is one questions that you need to answer - is there a company that you have missed to take a pen from? Some companies have many different types of pens.

You are interested in having at least one type of pen from each company at the event.

And since you are a programmer, you can use code to help yourself.

## Input / Output

Companies and their pens are going to be represented as list of lists. Each pen type is going to be denoted with a letter from `[a-z]`.

For example:

```
[ ['a', 'z'], ['c', 'd'], ['a', 'z', 'v'] ]
```

**This input means that there are 3 companies** and each list shows the type of pens the companies have.

You are going to be given a list of pen types per companies and a list of the pens you have collected at the end of the vent.

Implement a function that returns `true` if you have managed to collect at least one pen of each type. `False` otherwise.

## Signature

In a pseudo-language:

```
function enough_pens(pen_types, collected_pens) {

}
```

## Examples

```
enough_pens([ ['a', 'b', 'c'], ['d'], ['a'] ], ['b', 'c', 'd'])
==
False
```

In the example above, we can see that we have missed the type `'a'` pen from the third company. Damn!

---

```
enough_pens([ ['a'], ['b'], ['c'], ['d'], ['e', 'f', 'z', 'y'], ['a', 'b', 'c'] ],
            ['a', 'b', 'c', 'd', 'e', 'f'])
==
True
```

We have taken at least one type from each company.
