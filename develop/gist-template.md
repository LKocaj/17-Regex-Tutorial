# 17. Computer Science for JavaScript Challenge: Regex Tutorial

REGEX or Regular Expressions can be used to find certain patterns of characters within a string, a sequence of characters that defines a specific search pattern. Regex can be used to find certain patterns of characters within a string. They are also used frequently to validate input data.

## Summary

We'll use the expression used for matching hex values (the color code format system). Theres a standard format and a shorter version with only 3 characters describing the colors versus 6. 

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

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

# Regex Components

## Anchors -
### /`^`([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})`$`/
<br>

Anchors is a term refering to the beginning ` ^ ` or end ` $ ` of an expression, shown above.

## Quantifiers -
/^#`?`([a-f0-9]`{6}`|[a-f0-9]`{3}`)$/
<br>
Used to communicated how many characters are to be expected. Quantifiers set limits of a string that your regex matches. They will specify how many times a character, a group, or class must be present in the input for a match to be found. 

## OR Operator -
/^#?([a-f0-9]{6}`|`[a-f0-9]{3})$/

The OR operator within a given expression is defined using the `|` element. The OR operator indicates that it could either of the elements that we are separating with the line. HEX value can be either 3 or 6 in this sample.

## Character Classes -
/^#?(`[a-f0-9]`{6}|`[a-f0-9]{3}`)$/

Character classes can define a set of characters that can occur in input strings to fulfill a match. For aexample, a-f searches for letters a - f and 0 -9 searches for the numbers 0 - 9.

## Flags -

Regular expressions may have flags that affect the search.

## Grouping and Capturing -

Captures everything that is closed between the parenthesis. It isolates only  a part of the full match and assigns it an ID so it can be referred to later in the regex.

## Bracket Expressions -
/^#?`([a-f0-9]{6}|[a-f0-9]{3})`$/

We use parenthesis to define our bracket expression. This bracket expression shows the beginning of a character class or quantifier. 

## Greedy and Lazy Match -
/^#`?`([a-f0-9]{6}|[a-f0-9]{3})$/

The difference is that a greedy match will try to match an element as many times as possible. A lazy match will do the opposite and try to match as few times as possible to an element. Our example has a ? which would be lazy.

## Boundaries -

A boundary is a position between \w and \W (non-word char), or at the beginning or end of a string if it begins or ends with a word character. \b allows you to perform a “whole words only”. A “word character” is a character that can be used to form words. All characters that are not “word characters” are “non-word characters”.

## Back-references -

Back references are used to match a same text previously matched by a capturing group. This both helps in reusing previous parts of your pattern and in ensuring two pieces of a string will match.

## Look-ahead and Look-behind -

Look-ahead and Look-behind (together called look around) are assertions like start of a word or end of a line. Sometimes we need to find only those matches for a pattern that are followed or preceded by another pattern.

# Author -

Lawrence Kocaj

Web Developer in Westchester, New York taking the UCONN coding bootcamp.

Project Link: https://github.com/LKocaj/17-regex-tutorial