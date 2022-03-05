# vim knowledge

## variable scoping

| Name              | Initial | Description                                   |
|-------------------|---------|-----------------------------------------------|
| buffer-variable   | b       | Local to current buffer                       |
| window-variable   | w       | Local to current window                       |
| tabpage-variable  | t       | Local to current tabpage                      |
| global-variable   | g       | Global variable                               |
| local-variable    | l       | Local to current function                     |
| script-variable   | s       | Local to :sourced vim script                  |
| function-argument | a       | Function argument, only works inside function |
| vim-variable      | v       | Global variable, preferred by vim             |
