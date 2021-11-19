# fileorganizer
Hello everyone my name is Lav and in this video today we are going to talk about file organizer using python.

So, first of all we are going to import packages.

import os

import shutil

Now, create a variable name files in which list all the files present in the directory. 

Then we use for loop statement, so we can traverse through all the files.

So, we seprate file name and extention in every files.

Okay what is extension ?

For example- Any file name is LAV.PDF 

So, Lav is filename and (.) dot pdf is extention.

Now, we want to remove dot(.) then we write code like this extention=extention[1:]

Okay, now we are going to write if conditional statement.

If the extention directory already exists, then we move the file to that directory.

In else statement, we make a new directory and then we move the file into it.

So, Its done lets run this program.

