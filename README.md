# pretty_ls
![screenshot ls](https://github.com/cmicheledelaney/pretty_ls/blob/master/.screenshot_ls.png)  
file for dircolors to get a more colorful ls  

get the content of the file and save it as .LS_COLORS:    
`curl https://raw.githubusercontent.com/cmicheledelaney/pretty_ls/master/.LS_COLORS > .LS_COLORS`  
add this command to your .bashrc:  
`eval $(dircolors -b $HOME/.LS_COLORS)`  
the next time you start a new shell, ls will use the colors set in the .LS_COLORS file  
