# Title (replace with your title)

A REGEX also known as regular expression is a string that are texts to create patterns that help match, locate, and manage texts. There are ways to use REGEX and it does contain many Special patterns without needing Javascript, Python, and etc.

## Summary

The regex that i will be explaining in this tutorial is a Match emails. this will break this regex into indidviual components and how it maches a email. 


/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors
Anchors used in this regex expression for email are "^", This symbol shows that this is the behinning of the string and the dollar sign "$" is the end of the string.

### Quantifiers
Quantifier for this REGEX has the + operator, which connects the user's email address, email service, and .com, is included in this regex. The quantifier {2,6} is another one for this regex. It will allow for a match range of 2 to 6 characters for the [a-z\.] character set.


### Character Classes
Character calsses are specific notation used to denote matches between symbols in a particular group is called a character class. [a-z] A single case-sensitive character between a and z. This expression uses the character class \d, which matches a single character that is a digit from 0 to 9. It will only match a single number, like "6", but it won't match "66".


### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match



## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
# Regex
