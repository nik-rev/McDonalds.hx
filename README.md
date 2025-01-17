# McDonalds.hx

A b̸̧̛͍͎̱͈̟̞̦̖͐ͅͅͅé̷̢̛̥̗͙̤̗̦̱̰̲̳͌̾̈́̎͛̌a̵̢̛̦̣͉͈̦̞̝̤͎̱̜̍͐̐̐̾̋̐̚̕͝͝ǘ̸͖̓̏͑̐̉̉̀͐̚͘͘ț̴̫̺̝͎͙̯̔͂͊̿̈́͑̍̆͊̅͑̚͘͘͜͝ͅi̸̛̬͙̤͌̀̏̀̓̊̂̌͋̚͝͝f̴̧̫̰̘͙̝̂̽̅̆͐͆̒̋͒͗û̴̡͕̫̫͇̘̖̠̜̲͙̒̍͒̆͒̆̀̈̎͜l̸̛̼͗͆̎̉̈́͊͂͝ theme for the Helix editor.

## Screenshots

![image](https://github.com/user-attachments/assets/e55375f0-3d38-4f4c-9a31-ab09dd9e5247)

## Installation

Copy and paste the following into `~/.config/helix/themes/McDonalds.toml` (or wherever your Helix config lives):

```toml
"ui.selection" = { fg = "milk", bg = "mustard" }
"ui.cursor" = { fg = "milk", bg = "mustard" }
"ui.background" = { fg = "milk", bg = "ketchup" }
"ui.linenr" = "mustard"
"ui.statusline" = { bg = "milk", fg = "ketchup" }
"ui" = { fg = "milk", bg = "ketchup" }
"ui.virtual.ruler" = { underline = { style = "line" } }

"string" = { bg = "ketchup", fg = "mustard" }
"constant" = { bg = "ketchup", fg = "mustard" }
"comment" = { bg = "ketchup", fg = "mustard" }

"diff.plus" = "milk"
"diff.minus" = "milk"
"diff.delta" = "milk"

"warning" = { fg = "ketchup", bg = "milk" }
"error" = { fg = "ketchup", bg = "milk" }
"hint" = { fg = "ketchup", bg = "milk" }

"diagnostic" = { fg = "ketchup", bg = "milk" }


[palette]
ketchup = "#c1192a"
mustard = "#fdaf17"
milk = "#ffffff"
```
