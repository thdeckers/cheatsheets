# (n)Vim Plugins Cheat-Sheat


## Tabular
| :Tab/<char> | auto-align paragraph with <char> (example here :Tab/| ) |

## GitGutter
| <leader>hp | preview |
| <leader>hs | stage   |
| <leader>hu | undo    |

## Fugitiv
| :G add .  | git add .                  |
| :G diff   | git diff                   |
| :G commit | git commit                 |
| :Gread    | read index to working copy |

### :Gstatus
| :Gstatus           | git status                     |
| ctrl-n             | next file                      |
| ctrl-p             | previouse file                 |
| -                  | if file is not staged: git add |
| -                  | if file is staged remove it    |
| Enter              | review                         |
| :Gdiff (in Review) | show difference                |

## nerdcommenter
| [count]<leader>cc       | comment out                  |
| [count]<leader>cu       | uncomment the selected lines |
| [count]<leader>c<space> | toggle comment               |
| [count]<leader>ci       | toggle each line individualy |

## nerdtree
| <leader>n | toggle |

## vim-surround
| cs"' | change " to '      |
| ds"  | delete delimiter " |

## undotree
| <F5> | open undotree |

## easymotion
| <leader><leader>w  | trigger the word motion        |
| <leader><leader>fa | all a characters are hilighted |
