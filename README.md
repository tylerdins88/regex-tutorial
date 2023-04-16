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

Grouping constructs are used to group parts of a pattern together and apply quantifiers, alternations, or other operations to the group as a whole. These are enclosed in parentheses "( )" and can be used to create sub-expressions within a larger expression. There are two primary categories of grouping constructs: 

capturing group: "(pattern)" is a type of construct that captures the matched sub-expression and stores it in a numbered capture group, which can be referenced later. 

non-capturing group: "(?:pattern)" is a type of construct groups the sub-expression without capturing the matched text or storing it in a capture group. 

### Bracket Expressions

Anything inside a set of square brackets "[]" represents a range of characters that we want to match. This pattern is a bracket expression and can also be known as positive character group. Inside of the "[]" you can use a "-" to search for a range of alphanumeric characters. This is used to search through a string to make sure it has incudled certain characters that are deemed required. 

### Character Classes

A character class in a regex defines a set of characters, any one of which can occur in an input string to fulfill a match. Bracket expressions are considered character classes. 

"." matches any character except the new line character (\n)

\d matches any arabic numeral digit. 

\w matches any alphanumeric character from the basic Latic alphabet, including the underscore.

\s matches a single whitespace character, including tabs and line breaks. 

### The OR Operator

"|" the vertical bar is known as the OR operator. 

### Flags

We stated earlier that a regex must be wrapped in slash characters. Flags are the one exception. Flags are placed at the end of a regex, after the second slash, and they define additional functionality or limits for the regex. 

"g" is the global search the regex should be tested against all possible matches in a string. 

"i" case-insensitive search: case should be ignored while attempting a match in a string.

"m" multi-line search: a multi-line input string should be treat as multiple lines.

These are 3 of the main used flags. 

### Character Escapes

The backslash "\" in a regex escapes a character that otherwise would be interpreted literally.

## Author

This was written by Tyler Dinslage. I am a ever-learning web developer embracing technology everyday. Please see some of my work at https://github.com/tylerdins88
