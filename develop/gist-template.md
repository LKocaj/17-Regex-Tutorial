# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

## Character Classes -
/^#?(`[a-f0-9]`{6}|`[a-f0-9]{3}`)$/

## Flags -

## Grouping and Capturing -

## Bracket Expressions -
/^#?`([a-f0-9]{6}|[a-f0-9]{3})`$/

## Greedy and Lazy Match -
/^#`?`([a-f0-9]{6}|[a-f0-9]{3})$/

## Boundaries -

## Back-references -

## Look-ahead and Look-behind -

# Author -

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)