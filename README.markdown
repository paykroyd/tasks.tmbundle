# Tasks.tmbundle

[TextMate](http://macromates.com/) bundle for simple to-dos and notes. Based on the  [Tasks.tmbundle](http://github.com/henrik/tasks.tmbundle), which was inspired by [TaskPaper](http://www.hogbaysoftware.com/products/taskpaper). This also takes inspiration from emacs [org-mode](http://orgmode.org/). 

## Usage

Currently supports a very simple set of syntax. 
* prefix a line with - followed by a space to make it a task
* there are three levels of bullets \*, \*\*, and \*\*\* each followed by a space
* create a header by finishing the line with :
* To toggle a task between complete and pending use Cmd-D
* At the end of a line, hit Ctrl-Return to start the next line with the same task/bullet prefix as this line  
* To promote or demote the header of the current (e.g., turn a ** bullet into a * bullet or vice versa) hit Cmd-< or Cmd->


## Installation

### Without git

TODO

### With git, for hackers

In a terminal:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/paykroyd/tasks.tmbundle.git Tasks.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Original Credits and license for tasks.tmbundle

By [Henrik Nyh](http://henrik.nyh.se/) under the MIT license:

>  Copyright (c) 2007–2008 Henrik Nyh
>
>  Permission is hereby granted, free of charge, to any person obtaining a copy
>  of this software and associated documentation files (the "Software"), to deal
>  in the Software without restriction, including without limitation the rights
>  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
>  copies of the Software, and to permit persons to whom the Software is
>  furnished to do so, subject to the following conditions:
>
>  The above copyright notice and this permission notice shall be included in
>  all copies or substantial portions of the Software.
>
>  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
>  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
>  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
>  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
>  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
>  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
>  THE SOFTWARE.
