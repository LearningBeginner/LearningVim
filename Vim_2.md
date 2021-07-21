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