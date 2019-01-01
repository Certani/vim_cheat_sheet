# vim cheat sheet
WIP!!!

### Alternatives to hjkl:
How to reach the x-th character in a x-th line:\
xgg (xw) f&lt;character&gt;


___
### from [8 Vim Tips And Tricks That Will Make You A Pro User](https://itsfoss.com/pro-vim-tips/)
### Using variables to insert text:
&lt; normal mode &gt;

:ab anyname awful long term\
    --var-- ------extend to this------
    
i\
&lt; insert mode &gt;

This is an anyname example\
&lt; space &gt;\
This is an awful long term example
