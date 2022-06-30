# Colemak-DH-Vim
Vimscript function that allows you to use the standard qwerty bindings in normal mode when using the Colemak-DH keyboard layout.

```vimscript
function ColemakDHToQuertyNormalBindings()

    "Top row
    noremap q q
    noremap w w
    noremap f e
    noremap p r
    noremap b t
    
    noremap j y
    noremap l u
    noremap u i
    noremap ; p
    
    "Middle row
    noremap a a
    noremap r s
    noremap s d
    noremap t f
    noremap g g
    
    noremap m h
    noremap n j
    noremap e k
    noremap i l
    noremap o ;
    
    "Bottom row
    noremap z z
    noremap x x
    noremap c c
    noremap d v
    noremap v b

    noremap k n
    noremap h m
    noremap , ,
    noremap . .
    noremap / /

endfunction

call ColemakDHToQuertyNormalBindings()
```
