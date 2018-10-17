# clo

```python
import clo
import clo.c # as C
#from clo import O,F,S,N,H

# 中文
c-'打印123' #= print('123')

from clo import e,o #o=原文,e=英文

o.打印(123) #->o.印('123')


from clo import * # do something like / import future

print(123) #-> o.打印(123)
print['123'] #> same. not only one way to print number/ like perl?
print[0] # error. stack empty
print<<'21' # nothing
print[1] # -> 21
print-'2' # nothing?
print[2] # '1'

print() # -> py:print('1')
print[3] # =print[2], not really exist. like print[-1]

print+'a' # '1'->'1a'
print[4] # actually is print[3]

print>>'b' # '1a' -> 'b'
print[5]

print # repl>>> {打印:b}

str(print) # 'b'


```
