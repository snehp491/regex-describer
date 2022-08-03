# RegEx Crash Course

Regular expressions are used every where in software engineering. From validating a form input to parsing and performing operations on text, knowing a few regular expression short cuts can save you a lot of time and effort

## Summary

For this walk through, we're going to break down a common case of validating that a string provided by the user is in fact a valid email addres.
Matching an Email:

```/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/```


## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
Anchors allow us to slide a window of character matching and "anchor" it at some part of the string we are evaluating. For example, our string has ```([a-z\.]{2,6})$``` at the end, meaning we are looking for an exact character match at the end. In this case, website domains are required to be alphabet characters and between length 2 and 6 to be considered valid.

### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
