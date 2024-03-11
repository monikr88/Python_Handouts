# References
https://regex101.com/r/M5ZVY2/1

regex:
```python

"(?<!\d)\d{4}(?!\d)|(-+)\d{2}$|(\/+)\d{2}$"gm

```

test:

234.435.5768.34-23/34

'Date 24/04/2023

-23-22

44232 .2023

2023/12/10



https://www.w3schools.com/python/python_regex.asp

https://www.w3schools.com/python/trypython.asp?filename=demo_regex_match

https://learn.microsoft.com/en-us/dotnet/standard/base-types/regular-expression-language-quick-reference

# Code
```python
import re

if re.search("(-+)\d{2}$|\d{4}|(\/+)\d{2}$", date): # 2023-11-13
            
      date = " " + re.search("\d{2}$", re.search("(?<!\d)\d{4}(?!\d)|(-+)\d{2}$|(\/+)\d{2}$", date).group()).group()
```
