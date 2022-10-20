# Matching an Email- REGEX

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

## Summary
To match an email, the REGEX is going to look like the following:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

This is used to validate if the input matches an email address

## Table of Contents

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

The anchors include:
(^) - this indicates the beginning of the string
($) - this indicates the ending of the string

### Quantifiers

The quantifiers include:
(+) - this connects the users email name & email service & the .com
({2, 6}) - this allows a range from 2-6 characters for the set

### Grouping Constructs

Grouping Constructors include:
[a-z0-9_\.-] - this indicates the name of the email
[\da-z\.-] - this indicates the email provider
[a-z\.]{2,6} - this indicates the domain

### Bracket Expressions

Bracket Expressions include: 
[a-z0-9_\.-] - this matches any letter from a-z,  matches a character 0-9, & matches the characters "_" "-". 
[\da-z\.-] - this matches a single digit from 0=9, any character a-z, and the characters "." & "-".
[a-z\.]{2,6} - this matches any character a-z anf the character "."


### Character Classes

Charcater class single out certain characters in a bracket to match the regex:
a-z matches out characters between a-z
0-9 matches out characters between 0-9

### Character Escapes

Charcter Escapes match special meanings:
"\" before a character will match whatever follows it 
## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
