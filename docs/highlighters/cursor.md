zsh-syntax-highlighting / highlighters / cursor
-----------------------------------------------

This is the `cursor` highlighter, that highlights the cursor.


### How to tweak it

This highlighter defines the following styles:

* `cursor` - the style for the current cursor position

To override one of those styles, change its entry in `ZSH_HIGHLIGHT_STYLES`,
for example in `~/.zshrc`:

    ZSH_HIGHLIGHT_STYLES[cursor]='bg=blue'

The syntax for declaring styles is documented in [the `zshzle(1)` manual
page](http://zsh.sourceforge.net/Doc/Release/Zsh-Line-Editor.html#SEC135).