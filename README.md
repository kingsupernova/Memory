# Memory

我的互联网记忆，不论那些好的还是~~坏的~~，雁过留声，把看到的记录下来，**所有资料不保证客观独立**。

> Be happy

## `PeopleAroundYouAndMe`

> 一些普通人，到了网上却能指点江山，阴阳怪气(to be defined)
 
**TODO**
- [ ] 1  
- [ ] 2

## `Goverment`

> (to be defined)
> Related events 

**TODO**

 - [ ] 1
 - [ ] 2


## `说明`
-
 
-

>-
>>-
>>>-
>>>>-
 
## `链接`


```diff
+日出江花红胜火
-春来江水绿如蓝
```


```gantt
       dateFormat  YYYY-MM-DD
       title Adding GANTT diagram functionality to mermaid

       section A section
       Completed task            :done,    des1, 2014-01-06,2014-01-08
       Active task               :active,  des2, 2014-01-09, 3d
       Future task               :         des3, after des2, 5d
       Future task2              :         des4, after des3, 5d

       section Critical tasks
       Completed task in the critical line :crit, done, 2014-01-06,24h
       Implement parser and jison          :crit, done, after des1, 2d
       Create tests for parser             :crit, active, 3d
       Future task in critical line        :crit, 5d
       Create tests for renderer           :2d
       Add to mermaid                      :1d

       section Documentation
       Describe gantt syntax               :active, a1, after des1, 3d
       Add gantt diagram to demo page      :after a1  , 20h
       Add another diagram to demo page    :doc1, after a1  , 48h

       section Last section
       Describe gantt syntax               :after doc1, 3d
       Add gantt diagram to demo page      :20h
       Add another diagram to demo page    :48h
```