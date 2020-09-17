# Git - How to close commit editor?

## Solution:On Windows GIT Bash

## At First:
<kbd>Ctrl</kbd> + <kbd>X</kbd> ``` would do nothing and found out it works quite like vi/vim.``` 

## Then:
Press <kbd>i</kbd> ```to insert inline insert mode.Type the description at the very top```

## Then:
Press <kbd>esc</kbd>  ```to exit insert mode.```

## Then:
Type ``` :x! (now the cursor is at the bottom) and hit enter to save and exit.```

### Note: ``` If typing :q! instead, will exit the editor without saving (and commit will be aborted) ```
