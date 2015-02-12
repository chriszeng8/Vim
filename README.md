#vim commands
Feb 11 2015\
Chris.Z.Zeng 

####1.insert mode
simply press ```i```

####2.edit mode
However, insert ```i``` is generally not the way.
```esc``` or ```Ctrl-[```
The word "insert" will disappear.\

try ```i``` ```esc```, ```i``` ```esc``` a couple of times.

In edit mode, you can only enter vim commands.

####3.move up and down in edit mode
```j``` is going down\
```k``` is going up\
It makes sure to have them next to ```i```\
```h``` is left\
```l``` is right\

See more [Keyboard Layout](http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html)

####4.yank then paste (yy p command)
1.```yy``` = yank the whole row\
2.```p``` = paste\

**optional**: copy mutiple times by ```number-p```\
```5p``` copies it 5 times.\
Try 99p. Oops, how do I undo it?See below.

####5.undo (u or #dd)
1. ```u``` undo/go back\
2. number followed by ```dd``` with no space. e.g., ```5dd``` deletes 5 rows.

####6.join lines (capital J)
Capital J for join, since lowercase j is reserved for down

####7.save and quit
save (:w) ```:w a.txt``` save the file as a.txt\
quit (:q)


Source [Video](https://www.youtube.com/watch?v=71YTkxUNwmg)