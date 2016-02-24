```
pushd
```
This is a commmand that you can use to push into a different directory while  saving the work in your current directory. Basically this command 
will allow you to "save" your work without doing a git push while simultaneously taking you to a different directory. This is helpful for when you need to access another directory and you're not completely done with the work you are doing in the current directory. 

```
popd
```
This is a command that you can use to access the last directory you pushed from. When you perform a pushd it creates a "checkpoint", when you use popd
it will take you back to that checkpoint you created in the last directory. 



> Do More

```
(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ mkdir -p wecame/wesaw/weconquered

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ cd wecame/

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:wecame $ pushd wesaw/
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame/wesaw ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:wesaw $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame/wesaw

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:wesaw $ popd
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:wecame $ pushd ../
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ pushd ../..
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:learn_command_line_exercises $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:learn_command_line_exercises $ popd
~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp ~/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp/wecame

(master) Jarrod Jones
Jarrods-MacBook-Pro-2:tmp $ pwd
/Users/jarrodjones/workspace/davinci_coders_t1_2016/homework/learn_command_line_exercises/chapter_8/tmp
```
