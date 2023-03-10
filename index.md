# Lab Report 5

**Finding and Removing Files**

Source: [https://www.geeksforgeeks.org/find-command-in-linux-with-examples](https://www.geeksforgeeks.org/find-command-in-linux-with-examples)
```
[cs15lwi23avo@ieng6-201]:OUP:515$ cd Berk
[cs15lwi23avo@ieng6-201]:Berk:516$ ls
CH4.txt  ch1.txt  ch2.txt  ch7.txt
[cs15lwi23avo@ieng6-201]:Berk:517$ find . -type f -name "ch7.txt" -exec rm -f {} \;
[cs15lwi23avo@ieng6-201]:Berk:518$ ls
CH4.txt  ch1.txt  ch2.txt
```
This command works by finding the file using the name of the file and then using the remove command to remove it from the directory. It would be useful when you are trying to remove a file from a directory, but you don't exactly know where it is.

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
