# Regex Cheat Sheet

## The most commonly used metacharacters in Python, PHP, Perl, JavaScript, and Ruby

| Metacharacter | Meaning |
| ------------- |:------- |
| \n | Newline |
| [...] | Range |
| [^...] | Not in range |
| . | Any character except newline |
| \w | Word character [a-zA-Z0-9_] |
| \W | Nonword character [^a-zA-Z0-9_] |
| \d | Digit character [0-9] |
| \D | Nondigit character [^0-9] |
| \s | Whitespace character [\n\r\f\t] |
| \S | Nonwhitespace character [^\n\r\f\t] |
| ^ | Start of string |
| $ | End of string | 
| \b | Word boundary |
| \B | Not-word-boundary |
| i | Case-insensitive matching |
| m | ^ and $ match next to embedded \n |
| (...) | Group subpattern and capture submatch into \1, \2, .. |
| \n | Contains the result of nth earlier submatch from a parentheses capture group, or a named capture group |
| * | Match 0 or more times |
| + | Match 1 or more times |
| ? | Match 1 or 0 times | 
| {n} | Match exactly n times |

[http://regexcheatsheet.com](http://regexcheatsheet.com)
