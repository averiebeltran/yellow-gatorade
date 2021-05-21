# Matching An Email With Regex

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

## Summary

This file will describe the different components that make up a regex to match valid email addresses. The regex expression is: <pre><code>/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/</code></pre>

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

The ^ symbol signifies the start of the string we want to match. The $ signifies the end of the string we want to match. Everything in the regex in between these two symbols is what we want to match.

### Quantifiers

In the regex above, we have one quanitifier. The {} that contain {2,6} state that we can have between 2 and 6 copies of of the [a-z/.] sequence that comes before it.

### OR Operator

There are no OR operators in this regex.

### Character Classes

The character class \d matches a single character that is a digit. This is inside one of our bracket expressions.

### Flags

There are no Flags in this regex.

### Grouping and Capturing

The () create a capturing group. The capturing groups in this regex encapsulate the bracket expressions that we will match our results against.

### Bracket Expressions

There are three bracket expressions in the regex. The first expression [a-z0-9_\.-] matches a string that has values between a-z, 0-9 OR the special characters "_", ".", "-". The second expression [\da-z\.-] matches a string with a digit, a-z values, or the special characters ".", "-". The final expression [a-z\.] matches a string that has values between a-z or a ".".

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

Author: Averie Beltran
Github: https://github.com/averiebeltran
