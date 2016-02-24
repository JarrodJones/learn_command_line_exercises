The .. argument to cd will take the directory up by one. What I mean by this is that if you type the command 

```
cd ..    
``` 
it will take you to the previous directory from 

```
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_5
``` 
to 
```
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises
```



> cd to the joe directory with one command.

```
cd ~learn_command_line_exercises/chapter_4/tmp/stuff/things/frank/joe
```

> cd back to temp with one command, but not further above that.

```
cd ../ ../ ../ ../ ../ ../ ../
```

> Find out how to cd to your "home directory" with one command.

```
cd ~
```

> cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).

```
cd Documents/
```

> cd to your Downloads directory, then find it with your file browser.

```
cd Downloads/
```

> Find another directory with your file browser, then cd to it.
Remember when you put quotes around a directory with spaces in it? You can do that with any command. For example, if you
have a directory I Have Fun, then you can do: cd "I Have Fun"

```
cd ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_4/tmp/"I Have Fun"/
```
> Can you cd into the temp directory?

Yes you can cd into the tmp directory by typing cd tmp

```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_5 $ cd tmp
```
> Why don't we go into the temp directory?

I went into the tmp directory by typing cd (change directory).

```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_5 $ cd tmp

Jarrods-MacBook-Pro-2:tmp $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_5/tmp
```
> Can you go to the slash temp directory?

Yes you can go to the slash tmp directory by typing 
```
cd /tmp
```

> Can you go to the slash temp slash log directory?

In order to go to the /tmp/log directory you'll need to create a log directory in tmp.
```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_5 $ mkdir tmp/log
mkdir: tmp/log: File exists

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:chapter_5 $ cd tmp/log

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:log $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_5/tmp/log
```
