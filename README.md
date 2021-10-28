# Title regex_gist 

const regex = /[2-9]|[12]\d|3[0-6]+d/g;

## Summary

My regex code will match any number between 2-9 or any character in the set [12] either 1 or 2. \d will match any digit character 0-9 or matches character 3. Matches any character between [0-6]. d Character matches a "d" character(char code 100). Case sensitive. (gray|grey) will group multiple tokens together and create a capture group for extracting a substring or using a backreference. 

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Matching Fixed Strings, Matching Special Characters, Matching Character Sets,
Specifying Groups and Fields, Evaluating Occurrences, Specifying Location
Specifying Alternatives, Matching Information from a Table, Capturing Multiple Lines
Managing the Scope of Analysis
### Anchors
Anchors match a position before or after a character. ^ beginning of the text, $ end of the text
### Quantifiers
Quantifiers indicate numbers of characters or expressions to match. d Character matches a "d" character(char code 100). Case sensitive. 
### Grouping Constructs
Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string.
### Bracket Expressions
A bracket expression is a list of characters enclosed by ‘[’ and ‘]’. It matches any single character in that list.
### Character Classes
Character classes distinguish between kinds of characters like digits and letters. 
### The OR Operator
Acts like a boolean OR. Matches the expression before or after the |
### Flags
g — Global search, don’t return after the first match
### Character Escapes
The backslash in a regular expression precedes a literal character. You also escape certain letters that represent common character classes, such as \w for a word character or \s for a space.
## Author

Hi my name is Aaron Donelson, I am a Marine Corps veteran that had recently started my adventure in the programming world. You can see some of my work here https://github.com/addonelson