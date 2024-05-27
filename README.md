Requirements
Install "python3 -m pip install cmake-language-server"

"<leader> + n" - stop the "/" search.

comments are -> gc + motion

see todo comments to see more options like "BUG"
It shows on telescope
<comments> TODO:

"s" is now substitute

"ys + motion + surround characters"
Ex.: 

motion 
"motion" -> ys + w + ""
"cs" -> to change the surround
"cs old_character New_character"

"ds" - > To delete the surround
"ds surround character"

Works with tags aswell
"ys + motion + t (tag)" -> it will open a text box to write the tag
works with change and delete aswell


<!-- LSPs  -->
See all the LSP references "g+R" ang it will open it on telescope
Goto definitions "gd"
Get back from definitions "ctrl+o"

Goto type definitions = "gt"

move throug errors using "[d" and "]d"

"<leader> + ca" shows the recomendations on how to fix it

Smart rename on variables "<leader> + rn" and it will change all the instances of it in this and other files that are using ** 
See documentation "K"

If we change the name of a folder using the tree-setter "r" the folder on the files will change accordingly

Restart the language server "<leader> + rs"

