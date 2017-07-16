# python note

## str connect
can use "+" or "*"
```
>>> 'Hello' + ' ' + 'world'
'Hello world'
>>> 'Hello' * 4
'HelloHelloHelloHello'

```
"list" and "tuple" can use it too!!

## 'in' and 'not in'
```
>>> a=4
>>> b=5
>>> li = [1,2,5]
>>> a in li 
False
>>> b in li
True
>>> a not in li
True
```
## is/is not
## '*'
'*' can ignore some useless terms, and the parameter use '*' will be seen as string!
```
>>> x = [1,2,3,4,5]
>>> a,*b,c = x
>>> a,b,c
(0,[1,2,3],4)
```
## pass
always use in if-else to do nothing

## for ... in ...
for x in gg, and the type of gg can be "list","tuple","str"
```
name = (('jj',60,70),('kk',92,93),('kd',99,99))
highs = []
for x,y,z in name:
    if y >= 90 and z >= 90:
        highs += [x,y,z]
print(highs)
```
and the execution result is...
```
>>>['kk', 92, 93, 'kd', 99, 99]
```

## Reference
1.http://goo.gl/DJAKYW
2.https://goo.gl/usKfV5

