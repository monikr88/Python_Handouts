# References
https://regex101.com/r/M5ZVY2/1

regex:
(-+)\d{2}$|\d{4}|(\/+)\d{2}$

test:
234.435.5768.34-23/34
'Date 24/04/2023'
-23

https://www.w3schools.com/python/python_regex.asp

https://www.w3schools.com/python/trypython.asp?filename=demo_regex_match

https://learn.microsoft.com/en-us/dotnet/standard/base-types/regular-expression-language-quick-reference

# Code

import re
y = ""
if(re.search("(-+)\d{2}$|\d{4}|(\/+)\d{2}$", date)): # 2023-11-13
   y = re.search("\d{2}$", re.search("(-+)\d{2}$|\d{4}|(\/+)\d{2}$", date).group()).group()



