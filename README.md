# regex-tutorial

This is a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. Here you will see learn the definitions of each part and learn its importance.  

## Summary 

A regular expression, or regex, is a sequence of characters that forms a pattern used to match and manipulate strings of text. It is used in computer programming, text processing, and data validation. Various characters and special characters are used to define the search pattern. Regex Expressions can be used to validate email addresses, extract specific substrings from text, replace text, and more. 

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

Anchors are special characters that are used to represent specific positions in a string. The two main types are as follows:

"^" is the start of a line anchor. When placed at the start of a regex pattern, it ensures taht the pattern only matches if it occurs at the beginning of a line. 

"$" is the end of a line anchor. You place this at the end of a regex pattern to ensure the pattern matches. 

### Quantifiers

Quantifiers are special characters that are used to specify the number of occurrences of a particular pattern or character in a string. 

"*" matches zero or more occurrences of the preceding pattern.

"+" matches one or more occurrences of the preceding pattern.

"?" matches zero or one occurrence of the preceding pattern.

"{n}" curly brackets with a number specifies the exact matches you want of an occurrence in a preceding pattern. 

"{n, m}" curly brackets with two numbers specifies of range of matches you want an exact occurrence of in a preceding pattern. 

### Grouping Constructs

Grouping constructs are used to group parts of a pattern together and apply quantifiers, alternations, or other operations to the group as a whole. These are enclosed in parentheses "( )" and can be used to create sub-patterns within a larger parttern. There are several types of grouping constructs including but not limited to the following:

capturing group: "(pattern)" is a type of construct that captures the matched sub-pattern and stores it in a numbered capture group, which can be referenced later. 

non-capturing group: "(?:pattern)" is a type of construct 

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)