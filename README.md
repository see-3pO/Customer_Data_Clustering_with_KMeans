

**Useful Links:**

Project Link: 

Dataset Link: https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbFlmNmFfel9VaDl2QVlKbUZBVnFRa1VUa1pHZ3xBQ3Jtc0ttWUtadXdxb1ZIa0YxX1pJY0gwMnhRQVRHbnRNUU5RVGlPWXRaWTFSMlJUcHBIcWFCbjhaQVNoWkRqaTNuTE9TN3BNWnEtSENtMWJ3WWRyazBNalIzT1VNRjU3cFZleFFYR2ZudUtOODc3RWZSeE1obw&q=https%3A%2F%2Farchive.ics.uci.edu%2Fdataset%2F502%2Fonline%2Bretail%2Bii&v=afPJeQuVeuY


--Controlling the formatting of floats using pandas--

```python
import pandas as pd

# Set the display format for floats
pd.options.display.float_format = '{:20.2f}'.format

```
The `'{:20.2f}'` follows the following pattern
* 20 - The width of the field(totalnumber of characters including spaces). If number doesn't take up 20 characters, it will be right-aligned and padded with spaces on the left.

* .2f - Specifies the precision, a float with exactly 2 decimal places


This kind of formatting is useful when you want to create neatly aligned output, such as in tables or reports, where you need the numbers to line up correctly in columns.


