Matching Emails (Regex)

This tutorial will show you how to use regex to match emails with expression. This can be useful when validating emails with applications or technologies.

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

The expression that captures group #1 is ([a-z0-9_.-]+), which corresponds to the user's email address. ([da-z.-]+) is the second capturing group, and it will match the email service. The third and final capture group is ([a-z.]2,6] with the goal of capturing the.com.

### Bracket Expressions
The character sets [a-z0-9_\.-] for backed expressos for email validation are case-sensitive and match any letter a-z. Additionally, it finds matches for the characters "_" , "-" , and "."; [\da-z\.-]], which corresponds to any single digit from 0 to 9, any character from a to z (case sensitive), and the characters "." and "-".; [ [a-z] matches any a-z (case sensitive) character and the character ".".

### Greedy and Lazy Match
Greedy matches are included in this regex. It will match as many times as possible, giving back as necessary, as it includes the + Quantifier. Another one is when you use {} when the matching `{2,6} for the final capture group, this regex also makes use of a greedy quantifier with the value "."


## Author
Hanad Isse 

[I used Nicole Wallace as a resource](https://github.com/nicolewallace09)



