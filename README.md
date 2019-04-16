# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by the same factor (tripled) because the cost
of the constructor is linear.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked will grow by twice this facto (6 times)
because reigning champ is invoked twice for every
invocation of the constructor.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort will grow by
twice this facto (6 times) because the reigning champ
method will be used 3 times more (twice for every element)
and is invoked twice for every invocation of the constructor.
[Justify, in about 2 sentences.]
