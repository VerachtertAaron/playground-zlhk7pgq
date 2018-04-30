# Generics
New part, new topic! The next topic is Generics. Generics is all about adding generic type parameters to classes, methods etc. in order to make your code more flexible.
Generics is not something you commonly **need**, but it can be helpful when used correctly.

For those who recall the **PECS** rule, it can be quite frustrating to figure out if you need **super** or **extends**. In order to keep the exercises concise and not too complicated (relative to Generics of course, which can already be a mind-fuck), you don't necessarily need to use super to solve the exercises.

If you need to refresh your memory, you can check out some info [here](https://docs.oracle.com/javase/tutorial/java/generics/types.html).

The first exercise is to implement a function that calculates the union of two lists.
There is no code yet, but the second box contains a list of tests.
Work iteratively from the first test to the last, uncomment one test at a time.
You can only proceed once the test compiles and succeeds!

The tests use a class history that is as follows:

* `ChocolateCake` extends `Cake`
* `StuffedChocolateCake` extends `ChocolateCake`
* `VanillaCake` extends `Cake`

@[Write the implementation]({
    "stubs": ["src/main/java/generics/util/UnionUtil", "src/main/java/generics/util/UnionUtilTest"], 
    "command": "generics.util.UnionUtilTest"
})