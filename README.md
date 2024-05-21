# Drama File Processing
- Regular expression practice
- Drama file processing
-----------------
## Resolving Korean File Errors
```
import codecs
f = codecs.open('한글 파일.txt', 'r', encoding = 'utf8')
```
-----------------
## Regular Expression
How to find and process rules for specific characters. 

Example: Extracting only the email address, extracting only the phone number, extracting only the name of the cited scholar, etc. from an article.

### match vs search
**match**: The value can be found only if the pattern is the same from the beginning\
**serach**: Can find even if there is a pattern in the middle of the text

### Regular expression to find a pattern
You can learn more in the [Python docs](https://docs.python.org/ko/3/howto/regex.html).

### Controlling Greed
In regular expressions, it is greedy: it means swallowing up characters.
- Period (.): Meaning all characters → Characteristic of swallowing up all characters when repeated
- Stop greed: Question mark (?)
