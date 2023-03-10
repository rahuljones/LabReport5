# Lab Report 5

**Creating vertical tabs with echo**

Source: [https://www.tecmint.com/echo-command-in-linux/](https://www.tecmint.com/echo-command-in-linux/)
```
[cs15lwi23avo@ieng6-201]:~:498$ echo -e "\vThis \vis \vhow \vto \vdo \vvertical \vtabs"

This 
     is 
        how 
            to 
               do 
                  vertical 
                           tabs
```
This command works by adding a vertical tab to the back of each word that it touches. This would be useful when you want to show a cool message in your terminal

**Printing all of the files**

Source: [https://www.tecmint.com/echo-command-in-linux/](https://www.tecmint.com/echo-command-in-linux/)
```
[cs15lwi23avo@ieng6-201]:~:500$ echo *
bash-for-quiz lab3 lab7 path-examples perl5 skill-demo1-data wavelet
[cs15lwi23avo@ieng6-201]:~:501$ 
```
This command works by printing out all of the files that are found in the current directory. This is useful when you want to see which files are available to be accessed from that directory without using ls.

**Printing out text in red**

Source: [https://phoenixnap.com/kb/echo-command-linux](https://phoenixnap.com/kb/echo-command-linux)
```
[cs15lwi23avo@ieng6-201]:~:501$ echo -e '\033[0;31mThis-text-will-be-red'
This-text-will-be-red
[cs15lwi23avo@ieng6-201]:~:502$
```
This command works by changing the color of all the text into a different color once the command is used; even the next prompt becomes red. This would be useful to changing the color of the text to make it easier to see.
