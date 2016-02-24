> Can you remove the tmp directory?

Yes you can remove the tmp directory by typing:
```
$ cd ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_7/
$ rmdir tmp/stuff/things/frank/joe/alex/john/
$ rmdir tmp/stuff/things/frank/joe/alex/
$ rmdir tmp/stuff/things/frank/joe/
$ rmdir tmp/stuff/things/frank/
$ rmdir tmp/stuff/things/
$ rmdir tmp/stuff/
$ rmdir tmp/
```
You have to do it this way because your tmp file is not empty.

> Let's remove the tmp directory.


```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_7 $ rmdir tmp/
rmdir: tmp/: Directory not empty
```

When typing that command you receive an error because the directory is not empty. With that being said you would need to 
follow the steps I listed above and remove each subdirectory individually.
