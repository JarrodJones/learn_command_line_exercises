> Can you copy the foo.txt file to slash temp?  (Create foo.txt first...)

```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_10 $ ls
Readme.md foo.txt   tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_10 $ cp foo.txt tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_10 $ cd tmp/

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ ls
foo.txt

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_10/tmp
```


> Can you copy .bash_profile in your home directory to the current directory?

```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_10

(master) Jarrod Jones
Jarrods-MacBook-Pro-2: $cp ~/.bash_profile .bash_profile_copy_homework_practice

(master) Jarrod Jones
Jarrods-MacBook-Pro-2: $ ls
Readme.md   foo.txt     tmp

(master) Jarrod Jones
Jarrods-MacBook-Pro-2: $ ls .
./                                    .bash_profile_copy_homework_practice
../
```

> What is Robocopy?

Robocopy stands for "Robust file copy" and it is a file replication command. It is built into windows and adds additional features.
Additional features include but are not limited to: mirroring from source to destination so trees are in sync, scheduled copying, and the ability to copy file and folder names up to 32,000 characters without error. 
