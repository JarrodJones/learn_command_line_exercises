> Can you touch blah.txt?

We sure can. 
```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ touch blah.txt

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md blah.txt  tmp
```

> Let's create foo.txt.

Let's!
```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md blah.txt  tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ touch foo.txt

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md blah.txt  foo.txt   tmp
```


> What happens if you touch an existing file?

Lets see...

I believe that when you touch an existing file it overwrites it replacing the contents with an empty file. 
```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md blah.txt  foo.txt   tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ touch foo.txt

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md blah.txt  foo.txt   tmp
```

> Do More:

```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ mkdir tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ ls
Readme.md tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ cd tmp/

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ touch cant_touch_this.txt

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ ls
cant_touch_this.txt
```


```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ cd ..

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_9 $ rmdir tmp/
rmdir: tmp/: Directory not empty
```
You get the above error due to the fact that the directory is not empty because it contains the empty txt file "cant_touch_this"
