# Regex Cheat Sheet

## The most commonly used metacharacters in Python, PHP, Perl, JavaScript, and Ruby

| Metacharacter | Meaning |
| ------------- | ------- |
| \n | Newline |
| [...] | Range |
| [^...] | Not in range |
| . | (dot or point) Any character except newline |
| \w | Word character [a-zA-Z0-9_] |
| \W | Nonword character [^a-zA-Z0-9_] |
| \d | Digit character [0-9] |
| \D | Nondigit character [^0-9] |
| \s | Whitespace character [\n\r\f\t] |
| \S | Nonwhitespace character [^\n\r\f\t] |
| ^ | (caret) Start of string |
| $ | (dollar) End of string | 
| \b | Word boundary |
| \B | Not-word-boundary |
| i | Case-insensitive matching |
| m | ^ and $ match next to embedded \n |
| (...) | Group subpattern and capture submatch into \1, \2, .. |
| \n | Contains the result of nth earlier submatch from a parentheses capture group, or a named capture group |
| * | (asterisk or star) Match 0 or more times |
| + | (plus) Match 1 or more times |
| ? | (question mark) Match 1 or 0 times | 
| {n} | Match exactly n times |

## Python, PHP, Perl, JavaScript, and Ruby Supported Metacharacters

| Metacharacter | Meaning | Python | PHP | Perl | JavaScript | Ruby |
| ------------- | ------- | ------ | --- | ---- | ---------- | ---- |
| \a | Alert | x | x | x |  | x |
| \b | Backspace | x | x | x | x | x |
| \n | Newline | x | x | x | x | x |
| \r | Carriage return | x | x | x | x | x |
| \f | Form feed | x | x | x | x | x |
| \t | Horizontal tab | x | x | x | x | x |
| \octal | Character specified by a three-digit octal code | x | x | x |  |  |
| [...] | Range or character class | x | x | x | x | x |
| [^...] | Not in range or negated character class | x | x | x | x | x |
| . | (dot or point) Any character except newline | x | x | x | x | x |
| \w | Word character [a-zA-Z0-9_] | x | x | x | x | x |
| \W | Nonword character [^a-zA-Z0-9_] | x | x | x | x | x |
| \d | Digit character [0-9] | x | x | x | x | x |
| \D | Nondigit character [^0-9] | x | x | x | x | x |
| \s | Whitespace character [\n\r\f\t] | x | x | x | x | x |
| \S | Nonwhitespace character [^\n\r\f\t] | x | x | x | x | x |
| ^ | (caret) The start of the line of text | x | x | x | x | x |
| \A | Start of search string, in all match modes | x | x | x |  | x |
| $ | (dollar) The end of the line of text | x | x | x | x | x |
| \Z | End of string, or the point before a string-ending newline, in any match mode | x | x | x |  | x |
| \b | Word boundary | x | x | x | x | x |
| \B | Not-word-boundary | x | x | x | x | x |
| (?=…) | Positive lookahead | x | x | x | x | x |
| (?!…) | Negative lookahead | x | x | x | x | x |
| (?<=…) | Positive lookbehind | x | x | x |  | x |
| (?<!…) | Negative lookbehind | x | x | x |  | x |
| i | Case-insensitive matching | x | x | x | x | x |
| m | ^ and $ match next to embedded \n | x | x | x | x | x |
| s | Dot (.) matches newline | x | x | x |  |  |
| x | Ignore whitespace, and allow comments (#) in pattern | x | x | x |  | x |
| (?mode) | Turn list modes on for the rest of the subexpression | x | x | x |  |  |
| (?#...) | Treat substring as a comment | x | x | x |  | x |
| #... | Rest of the line is treated as a comment in x mode | x | x | x |  | x |
| (…) | Group subpattern and capture submatch into \1, \2, .. | x | x | x | x | x |
| \n | Contains the result of nth earlier submatch from a parentheses capture group, or a named capture group | x | x | x | x | x |
| (?:…) | Groups subpattern, but does not capture submatch | x | x | x | x | x |
| …\|… | Try subpatterns in alternation | x | x | x | x | x |
| * | (asterisk or star) Match 0 or more times | x | x | x | x | x |
| + | (plus) Match 1 or more times | x | x | x | x | x |
| ? | (question mark) Match 1 or 0 times | x | x | x | x | x |
| {n} | Match exactly n times | x | x | x | x | x |
| {n,} | Match at least n times |  | x | x | x | x |
| {x,y} | Match at least x times, but no more than y times | x | x | x | x | x |
| *? | Match 0 or more times, but a few times as possible | x | x | x | x | x |
| +? | Match 1 or more times, but a few times as possible | x | x | x | x | x |
| ?? | Match 0 or 1 times, but as few times as possible | x | x | x | x | x |
| {x,y}? | Match at least x times, no more than y times, and as few times as possible | x | x | x | x | x |










