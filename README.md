# vim cheat sheet
WIP!!!

### Alternatives to hjkl:
How to reach the x-th character in a x-th line:\
&lt; normal mode &gt;

__xgg__ __(xw)__ __f&lt;character&gt;__
___
### Using variables to insert text:
##### from [8 Vim Tips And Tricks That Will Make You A Pro User](https://itsfoss.com/pro-vim-tips/)
&lt; normal mode &gt;

__:ab__ __anyname__ __awful__ __long__ __term__\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  ----var----&nbsp; --extend to this--
    
**i**\
&lt; insert mode &gt;

This is an anyname example\
**&lt;** **space** **&gt;**\
This is an awful long term example
___
### write and quit
#### from [Best Vim Tips](http://vim.wikia.com/wiki/Best_Vim_Tips)
&lt; normal mode &gt;\
**:wq** = **:x**
___
### Open two files in two splitted windows
#### from [8 Interesting ‘Vi/Vim’ Editor Tips and Tricks for Every Linux Administrator – Part 2](https://www.tecmint.com/how-to-use-vi-and-vim-editor-in-linux/)

horizontal split (lower case o):\
**vim -o file1 file2**

vertical split (upper case O):\
**vim -O file1 file2**
