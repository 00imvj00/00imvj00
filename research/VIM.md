# vim knowledge

## Components 

TODO

## Modes

| Mode         | Description                                                                     |
|--------------|---------------------------------------------------------------------------------|
| Normal       | vim's primary mode, the one we use to run commands                              |
| Insert       | The mode where you edit the content of the files and buffers                    |
| Visual       | Visual selection and searching of the content                                   |
| Replace      | Allows you to type over text and replacing it.                                  |
| Command-Line | Allows you to execute commands via it's own command-line prompt                 |
| Visual-block | allows you to make block level changes, vertical selection and changes          |
| Ex           | in this mode vim emulates the Ex editor and is used mainly for batch processing |

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


## mappings

TODO

## autoCommands

TODO
