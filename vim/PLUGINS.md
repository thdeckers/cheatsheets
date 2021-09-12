# (n)Vim Plugins Cheat-Sheat


## Tabular
| command     | description                                          |
| ---         | ---                                                  |
| :Tab/<char> | auto-align paragraph with <char> (example here :Tab/ | ) |

## GitGutter
| command    | description |
| ---        | ---         |
| <leader>hp | preview     |
| <leader>hs | stage       |
| <leader>hu | undo        |

## Fugitiv
| command   | description                |
| ---       | ---                        |
| :G add .  | git add .                  |
| :G diff   | git diff                   |
| :G commit | git commit                 |
| :Gread    | read index to working copy |

### :Gstatus
| command            | description                    |
| ---                | ---                            |
| :Gstatus           | git status                     |
| ctrl-n             | next file                      |
| ctrl-p             | previouse file                 |
| -                  | if file is not staged: git add |
| -                  | if file is staged remove it    |
| Enter              | review                         |
| :Gdiff (in Review) | show difference                |

## nerdcommenter
| command                 | description                  |
| ---                     | ---                          |
| [count]<leader>cc       | comment out                  |
| [count]<leader>cu       | uncomment the selected lines |
| [count]<leader>c<space> | toggle comment               |
| [count]<leader>ci       | toggle each line individualy |

## nerdtree
| command   | description |
| ---       | ---         |
| <leader>n | toggle      |

## vim-surround
| command | description        |
| ---     | ---                |
| cs"'    | change " to '      |
| ds"     | delete delimiter " |

## undotree
| command | description   |
| ---     | ---           |
| <F5>    | open undotree |

## easymotion
| command            | description                    |
| ---                | ---                            |
| <leader><leader>w  | trigger the word motion        |
| <leader><leader>fa | all a characters are hilighted |
