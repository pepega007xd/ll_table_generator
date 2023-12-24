# LL-table generator

Stolen from [here](https://www.cs.princeton.edu/courses/archive/spring20/cos320/LL1/),
modified so that the resulting LL-table is not absolutely huge.

## Grammar format

Just prepend every rule with a number, from this

```
ADD ::= E + E
SUB ::= E - E
```

make this

```
01 ADD ::= E + E
02 SUB ::= E - E
```

The numbers are then shown in the LL-table instead of the whole rules, which makes it
much smaller.
