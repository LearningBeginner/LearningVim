# Substitute
```
# In a line
:s/old/new/g <ENTER>

# only changes the first occurrence
:s/old/new <ENTER>

# Line interval can be determined(#,# are the line numbers of the range)
:#,#s/old/new/g <ENTER>

# To change every occurrence.
:%s/old/new/g <ENTER>

# To find every occurrence, with a prompt.
:%s/old/new/gc <ENTER>
```
# Find a Letter In a Line
`f` : find a letter  
`F` : backward  
`t` : one point forward,,than f  
`T` : baakward version  
`;`, `,`(backward) can be used to repeat the command

# Scrolling around
## H(high), M(middle), L(low)
on one screen

## ctrl b, ctrl f
last 2 line or first 2 line to...

## ctrl u, ctrl d
middle line to up first or last line

## CTRL e, ctrl y
one line scroll

## zz
line with cursor to middle

## zt zb
line with cursor to top or bottom

# jump
Generally, every time you do a command that can move the cursor further than within the same line, this is called a jump.

```
`` or '' : go back where you came from using jump  
Simmilarly, Ctrl O  
backward : Ctrl I of Tab  
using :jump, you can check the list of jumps.  

you can set a mark using ma / ms / ...  
and go to that point using 'a / 's / ...  
:marks to check a marked points.  

there are special marks like   
'  
"  
[  
]  

```

# Retriving and merging files
To insert the contents of a file, type `:r FILENAME`. You can also `:r !ls`.


# set option for searching 
```
# ignore case
:set ic
# /ignore\c -> ignore case for just one search command

# highlight all matching phrases
:set hls

# show partial matches for a search phrase(incsearch)
:set is

# disable
:set noic
:set nohlsearch

# temporarly disable
:nohls 

# at once
:set hls ic
```