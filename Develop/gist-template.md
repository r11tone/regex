# Title 
What is Regex?

## Summary

Regex is a pattern-matching language used to search, manipulate, and validate text data. It allows users to define a set of rules that specify how a particular pattern should look and be matched within a text. It's a powerful tool for working with text data and can be used in a variety of programming languages and applications.

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
### Anchors:
Anchors: Anchors are special characters used to specify the position of a match in a string. Examples include "^" for the start of a line, and "$" for the end of a line.

### Quantifiers:
Quantifiers: Quantifiers specify how many times a character or group should be matched. Examples include "*", which matches zero or more occurrences, and "+" which matches one or more occurrences.

### OR Operator:
OR Operator: The OR operator, denoted by the "|" character, allows you to match either one pattern or another. For example, the regex "cat|dog" would match either "cat" or "dog".

### Character Classes:
Character Classes: Character classes allow you to match a group of characters. Examples include "[a-z]" which matches any lowercase letter, and "[0-9]" which matches any digit.

### Flags:
Flags: Flags modify the behavior of a regular expression. Examples include "g" which performs a global search, and "i" which performs a case-insensitive search.

### Grouping and Capturing:
Grouping and Capturing: Grouping allows you to match a group of characters and capture them for later use. This is done using parentheses. For example, the regex "(abc)+" would match one or more occurrences of the sequence "abc".

### Bracket Expressions:
Bracket Expressions: Bracket expressions match any one of a set of characters. For example, the regex "[abc]" would match any occurrence of "a", "b", or "c".

### Greedy and Lazy Match:
Greedy and Lazy Match: Greedy matching tries to match as much as possible, while lazy matching tries to match as little as possible. This is denoted by the use of "?" after a quantifier.

### Boundaries:
Boundaries: Boundaries are used to specify the beginning or end of a word. Examples include "\b" for a word boundary, and "\B" for a non-word boundary.

### Back-references:
Back-references: Back-references allow you to match a previously captured group. This is done using a backslash followed by the group number. For example, "\1" would match the first captured group.

### Look-ahead and Look-behind:
Look-ahead and Look-behind: Look-ahead and look-behind allow you to match a pattern only if it is followed by or preceded by another pattern, without including the other pattern in the match. This is done using the syntax "(?=pattern)" for look-ahead and "(?<=pattern)" for look-behind.

## Author:
Tyler Ritone
https://github.com/r11tone
