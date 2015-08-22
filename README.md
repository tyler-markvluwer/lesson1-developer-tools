# lesson1-developer-tools
## Lesson 1: A lesson outline and rough tutorial on how to use tools more efficiently.

## Purpose:
Your ability to code and solve problems is only a small part of your effectiveness as a developer. It is equally important that you can work quickly and stay organized. It doesn't matter how good your code is if you take twice as long to write your code as everyone else on your team. If you are the best, but slowest intern this often means not finishing your project and not receiving a return offer. That is why we will spend this time reviewing the tools you are using and going over how to increase your efficiency.

## Preconditions:
We will assume throughout these lessons that you are using a linux/unix OS. If you are not familiar with these environments or the command line then this lesson will be especially important for you. You may need to review a basic command line tutorial first though to fully understand. This lesson is intended to introduce mid-level tools to someone who already has basic understanding.

## Tools:
You are not required to use any of these tools, but if you choose to use other tools, I will not help trouble shoot your issues, whether they are tool related or code related.

### Text editor: Sublime Text 2 or 3 --> http://www.sublimetext.com/2
<ul>
  <li>Make sure that you are able to open files from the command line. e.g. subl test.txt<li>
  <li>Install coffeescript plugin for sublime. The following link may be helpful --> http://blog.artillery.com/2014/06/working-with-coffeescript-sublime-text.html</li>
  <li>You can also optionally install emmet plugin, though we won't be writing much raw HTML</li>
</ul>

### Terminal/Environment:
More detailed instructions (tested for Mac) are provided in another repo. We will cover this in class

### Browser:
You must have chrome installed. Chrome is particularly useful for stepping through javascript code, simulating mobile screens, among other uses.

## Using the tools:
Now that you have the actual list of tools, I will show you what is so special about each. Many of these features may also transfer between tools, so if something seems intuitive from one tool to another, try it out! Especially between Sublime and the terminal.

### Sublime:
#### Multiple cursors:
You can create multiple cursors at a time by using the 'command' + click, but you can also do so using the 'command' + 'd'. command-d is especially useful because it highlights the next instance of what your cursor is currently over.
### Opening files from keyboard:
By pressing 'command' + 'p' you will see a window open at the top. Start typing the name of a file which is in the open directory and you can open it directly into that sublime window. This works with partial matches as well. For instance, if I want to open testFile.py, I can type 'estil' and it will match, because all letters are found and in the correct order.
### Switching between open tabs:
'command' + 'shift' + '}' will change your current tab, to the tab to the right. The same can be done with the '{' as well to go to the left. Also works in Chrome and terminal.
### Command + arrow:
using command + 'left' or 'right' will jump to the beginning or end of the line. 'Option' will jump to the next token, instead of jumping to either extreme. Option is extremely useful.
### Command + 'x':
This will delete the line that the cursor is currently on, while 'cutting it'. That means you can paste the entire line (which includes a newline) using command + 'v'. This only works if the cursor is not highlighting anything.
### ctrl + 'g':
Opens a prompt and jumps to a line in the file. To return to your location where your cursor was before using ctrl+g, simply press esc instead of enter.
### fn + f5:
This will sort the text that is selected. This is particularly useful for sorting import statements which is common practice in many companies.
### Add more of your own here! I'm sure I forgot some...



