# Computer Science for JavaScript: Regex Tutorial

In this tutorial it will explain how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does. 

## Summary

Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the exec() and test() methods of RegExp, and with the match(), matchAll(), replace(), replaceAll(), search(), and split() methods of String. 

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
Regexes are composed of a range of different components that work together to define a search pattern. The most common components include anchors, character classes, quantifiers, and alternation.

### Anchors
Anchors provide a way to limit how a regex matches a certain string by telling the regex engine where matches can begin and where they can end. What they do is ensure that a regex matches a string at a specific place: the beginning or end of the string or end of a line, or on a word or non-word boundary.

### Quantifiers
Quantifiers indicate numbers of characters or expressions to match.
![alt text](./images/Screen%20Shot%202023-05-24%20at%2010.08.54%20PM.png)


### Grouping Constructs
Grouping constructs setout the subexpressions of a regular expression and capture the substrings of an input string. You can use grouping constructs to do the following:
Match a subexpression that's repeated in the input string.
Apply a quantifier to a subexpression that has multiple regular expression language elements.
Include a subexpression in the string that's returned by the Regex.Replace and Match.Result methods.
Retrieve individual subexpressions from the Match.Groups property and process them separately from the matched text as a whole.



### Bracket Expressions
A bracket expression is anything found within brackets ([]) that creates a range of characters that tell us what we want to match within the text. For example, we can find three bracket expressions: [0-9], [a-z], and [_. -]. [0-9] depicts any number between 0 and 9.

### Character Classes
The character class is the most basic regex concept after a literal match. It makes one small sequence of characters match a larger set of characters. For example, [A-Z] could stand for any uppercase letter in the English alphabet, and \d could mean any digit. 

### The OR Operator
A JavaScript RegEx is a sequence of characters that forms a search pattern. You can define what needs to be searched in a text with the help of regular expressions. These expressions can be of any number of characters, be it alphabets-letters, digits or special characters.

### Flags
A flag is an optional parameter to a regex that modifies its behavior of searching.

### Character Escapes
Escapes a minimal set of characters (\, *, +, ?, |, {, [, (,), ^, $, ., #, and white space) by replacing them with their escape codes. This instructs the regular expression engine to interpret these characters literally rather than as metacharacters.

## Author

Alexia Valenzuela https://github.com/alexiaValen

