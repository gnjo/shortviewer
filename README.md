# echoo

//keycall jump select output wait modechange
//message five, choice 1+4
```
$$m //mode
$$k //key
$$n //select number
$$s //select list
$$o //output
$$a //nowaddress
$$l //nowread line
$$j //jumpback line
$$$ //return

#mark
m>xyz //mode change
k> //keywait
>{$$n} //output select number
> //clear
>choice is are?
{{{
aaa
bbb
ccc
ddd
}}}
s>{$$$}
**** //one astrisk wait 50ms
{1}>>>#aaaa
```

```
echooRead(text)
function echoo(str,o){
 //callback;
}
```
