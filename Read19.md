### [Python Regular Expressions Tutorial](https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial)
* regular expression: regex, re library. Used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc.
* import re
* r"str": r-raw string literal
* Ordinary Characters. 
* Wild Card Characters: Special Characters. 
  * . - A period. Matches any single character except the newline character.
  * ^ - A caret. Matches the start of the string.
  * $ - Matches the end of string.
  * [abc] - Matches a or b or c.
  * [a-zA-Z0-9] - Matches any letter from (a to z) or (A to Z) or (0 to 9).
  * \ - 
    * If the character following the backslash is a recognized escape character, then the special meaning of the term is taken
    * if the character following the \ is not a recognized escape character, then the \ is treated like any other character and passed through
    * can be used in front of all the metacharacters to remove their special meaning
  * \w - Lowercase 'w'. Matches any single letter, digit, or underscore.
  * \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).
  * \s - Lowercase 's'. Matches a single whitespace character like: space, newline, tab, return.
  * \S - Uppercase 'S'. Matches any character not part of \s (lowercase s).
  * \d - Lowercase d. Matches decimal digit 0-9.
  * \D - Uppercase d. Matches any character that is not a decimal digit.
  * \t - Lowercase t. Matches tab.\n - Lowercase n. Matches newline.
  * \r - Lowercase r. Matches return.
  * \A - Uppercase a. Matches only at the start of the string. Works across multiple lines as well.
  * \Z - Uppercase z. Matches only at the end of the string.
  * \b - Lowercase b. Matches only the beginning or end of the word.
  *  +  - Checks if the preceding character appears one or more times starting from that position.
  *  * - Checks if the preceding character appears zero or more times starting from that position.
  *  ? - Checks if the preceding character appears exactly zero or one time starting from that position.
  * {x} - Repeat exactly x number of times.
  * {x,} - Repeat at least x times or more.
  * {x, y} - Repeat at least x times but no more than y times.
* <.*>:  matched the whole string, right up to the second occurrence of >
* re.compile(pattern, flags=0)
* re.search(pattern, string, flags=0)
* re.match(pattern, string, flags=0)
* re.findall(pattern, string, flags=0)
* re.sub(pattern, repl, string, count=0, flags=0)
* re.subn(pattern, repl, string, count=0)
* re.split(string, [maxsplit = 0])
* match.start()
* match.end()
* match.span()

### [shutil](https://pymotw.com/3/shutil/)
* shutil module includes high-level file operations such as copying and archiving
* import shutil
* Copying Files
* Copying File Metadata
* Working With Directory Trees
* Finding Files
* Archives
* File System Space

### Videos:
### [Automation Ideas](https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s)
### [Optional: Automating Your Browser and Desktop Apps](https://www.youtube.com/watch?v=dZLyfbSQPXI)

### Bookmark
### [Watchdog](https://pythonhosted.org/watchdog/)

[<--Back](README.md)