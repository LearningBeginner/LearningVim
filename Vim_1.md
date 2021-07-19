# [Shift-A] & [Shift-I]
```
Shift-A = $a
Shift-I = ^i
```
# Delete skill
```
[d (+ number) + motion]
```
## You can also use `c` instead of `d` (to replace).

# Ctrl-G
Show your location in the file and the file status.

# % 
* To find a matching ),], or }.
* 90% = Go to 90% line of a document. 
# Replace  
`R` : replace more than one character

# yw
yank a word

# Going to the other side in visual mode
o or O

# moving around
```
w, W, b, B, ge, e, gE, E 
```
* [consider `.`, `-`, `)`, ...]

# Visual block : Ctrl-V
Vertical check

# Selecting Text to Write
To save part of the file, type `:w FILENAME` in the VISUAL mode.

# Search Command
You can a word or phrase using `/` or `?` (backward), and `n` and `N` (backward).  
To go back to where you came from, use `Ctrl-O`. `Ctrl-I` goes forward.  

---

The characters `.*[]^%/\?~$` have special meanings.  
If you want to use them in a **search** you must put a `\` in front of them.

---

Command `*` find **words** under the cursor. `#` for other direction.  

---

`\>` : special marker that only matche at the end of a word  
`\<` : simmilarly, beginning of a word  
Example:  
`/the\>` : find 'the' not 'there'

---

The `^` matches the beginning of a line  
The `$` matches the end of a line  

---

the `.`(dot) matches any existing character.  
Example:  
`\c.m` -> cam, cim, cpm, ...
