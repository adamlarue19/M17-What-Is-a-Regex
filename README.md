# M17-What-Is-a-Regex
This is M17 Challenge called What is a regex.

# Regex tutorial for [a-z0-9_-]



## Summary

  This tutorial will explain the details of a unique regex. This regex is [a-z0-9_-]. This expression will search for everything inside of the brackets. Inside the brackets we have a-z0-9 -. a-z is referencing the whole alphabet a through the letter z. since the letters are lowercase  we will be searching for letters that are lowercase while within that range. Next we have 0-9, which references every number between 0-9, so everything that contains lowercase letters or numbers 1-9 will match this regex. Finally we have the hyphen and underscore. This represents any string that contains the characters of either the dash or underscore.

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

An example of an anchor would be the ^ symbol. This signals the begginging of a string.

### Quantifiers

Quantifiers specificy how many of a character needs to be present in a string for there to be a match in the regex, for example requiring 4 2's.

### Grouping Constructs

Grouping constructs is a way to query with regex and return several subsets of information that have something in common.

### Bracket Expressions

A bracket expression will simply query everything within the brackets using regex. In example [a-z0-9] every lowercase letter between a and z would cause a match as well as any present numbers.

### Character Classes

Character classes are used to distinguish between certain sets of characters. For example this would include using regex to find matches on strings that have vowels but not consonants in them.

### The OR Operator

The OR operator is displayed with | and it allwos you to regex between preselected options. An example would be are you looking for Tigers or Bananas. Another example would be (Gatoraid|Bleech) which equals Gatoraid or Bleech.

### Flags

Flags are modifiers that allow you to affect the engine which you search with. For example using "g" would allow you to regex a global match and continuing after the first match.

## Author
My Name is Adam Larue
https://github.com/adamlarue19
