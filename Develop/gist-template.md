# Corbin's RegEx tutorial (Matching an HTML Tag)

Hello user! Today, I'll be explaining the functionality of a concept of the coding world called a "Regular Expression". 
However, the name may decieve you because these expressions are far from regular. When the word expression comes to mind, we all start to think back to high school math expressions, such as, y = mx + b or the pythagorean theorem. These expressions, in fact, are far more difficult to understand.

## Summary

HTML Tag Matching RegEx

/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/

First of all, every RegEx starts with /^ and ends with $/. Now, in order to have this regular expression search for and match an html tag, we have to go over what an html tag consists of. <header> </header> is an opening and closing html tag that allows a developer to insert a header onto the page they are building. All we have to do now is specify what to look for within the RegEx. 



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

The components of the RegEx shown above consist of Anchors, Bracket Expressions, Grouping Constructs, Groups and Backreferences, and the Or Operator.

### Anchors

The HTML matching RegEx example above starts with the /^ anchor and ends with the $/ anchor. 

### Quantifiers

The + symbol is a quantifier that allows us to match any number of times as long as the character is lowercase and is a to z.

### OR Operator

The Or operator is present towards the end of our RegEx. 

### Grouping and Capturing

There are a few groupings in our HTML tag regex. The first one is [a-z] which matches any lowercase letters. Next, we have [^<]+ which will allow for any classes or id's. Then, we have a non-capturing group which is 
(?:>(.*). This non-capturing group only allows for a > character but will not need to be remembered later.

### Bracket Expressions

Our examples of bracket expressions would be what is in our groupings above.

## Author

My name is Corbin. I am a student at the Georgia Tech Coding Bootcamp. I love to code and I plan on building websites for others very soon! Here is a link to my GitHub profile https://github.com/Cutter25
