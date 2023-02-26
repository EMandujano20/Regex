# REGEX Tutorial - Matching a URL
This tutorial will go over how a regex fot matching a URL works

## Summary
This explains how a regular expression or regex that defines the pattern for matching a URL. The following characters are used, 
```
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```

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

### Anchors
Anchors are used to describe the beginning and end of a string. The beginning of the string would use ```^``` and the end of the string would use ```$```. Iw would look like `^Hello$`

### Quantifiers
Quantifers are used in how we read each characters in the regex. A URL uses these quantifers,
    <br>`(https?:\/\/)?`<br>
    <br>`https`: would allow the string to use `http` 
    <br>

### OR Operator
The OR operator could be used with `|` to match patterns in a regex. An example is `/^I'm going to buy (carrots|peas$/)`
### Character Classes
In a regex, characters are categorized into classes. 
<br>
`/d` is used for single characters from 0 to 9.
<br>
`/w` id used for single characters that can be numeric or an underscore.

### Flags

### Grouping and Capturing

### Bracket Expressions
The bracket character `[]` is used to martch a set of characters `[abc]`

### Greedy and Lazy Match
 The lazy match is `?` and can only capture a zero and a single pattern 
 <br>
 the Greedy math is `+ * or {}` 

### Boundaries
Boundaries are used to looking at wholw works. When searching for the whole word, it would be surround by `/b`

### Back-references

### Look-ahead and Look-behind

## Author

Created by Eduardo Mandujano | [GitHub](github.com/EMandujano20) | [GMAIL](mandujanolalo@gmail.com)