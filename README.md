# Ragex 

# table of contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Pattern: 
/^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/

phone number formats: 
(555) 555-5555
555-555-5555
555.555.5555
555 555 5555

The tutorial will include the following sections:

## Anchors: 
usage of ^ and $ as anchors to match the start and end of a string.

## Quantifiers: 
Usage of + and {2,} as quantifiers to match one or more characters.

## OR Operator: 
Using symbols as the OR operator to match multiple alternatives.

## Character Classes: 
[a-zA-Z0-9._%+-] and [a-zA-Z] as character classes to match specific characters.

## Flags: 
Using flags to modify regex behavior.

## Grouping and Capturing: 
Using parentheses for grouping and capturing. example (555) represents the area code of a phone number.

## Bracket Expressions: 
Square brackets are used for creating custom character classes. [] is used to match the -, ., or space.

## Greedy and Lazy Match: 
Explanation of greedy and lazy quantifiers.

## Boundaries: 
Explanation of \b for word boundaries.

## back-references: 
Explanation of using \1 for back-referencing captured groups.
Look-ahead and Look-behind: Explanation of look-ahead and look-behind assertions.
