# My Vim Docs
创建这个repo是为了我使用Vim再上一个层次 <br />
我的想法是这个的，把一些Vim文档中个人觉得非常实用的东西但自己又不会的分类整理在这里 <br />
然后呢，平时使用Vim的时候顺带用上，什么时候觉得自己会了，就把那条命令删掉 <br />

## jumps, marks (from usr_03)
`:ju[mps]` <br />
`:cle[arjumps]` <br />
`m'` <br />

另外跳行操作`:n`和`nG`(这个n代表你要跳到哪一行) <br />
只有`nG`会把将原来的位置加入jump list <br /> 

`'"`			跳到上次编辑退出时候的光标位置 <br />
`'[`			最后一次进入编辑模式的地方 <br />
`']`			最后一次退出编辑模式的地方 <br />

## Making small changes (usr_04)
`D`
`C`
`X`
`s`

`y2w` `y2e` diff? <br />
`cis`

`dw` `db`

## usr_05
`:options`

## usr_07
`:ar[gs]` `:args *.txt`

`:fir[st]` `:la[st]`

`:n[ext]` `:N[ext]`

`C-^`

`'"` `'.`

`delm[arks]`

`"fyas`

`vim -R file` `vim -M file`

`:sav[eas]` `:f[ile]`


## usr_08
`:clo[se]` or `C-W_c` <br />
`:on[ly]` or `C-W_o` <br />
`sp[lit]` or `C-W_s` <br />
`{height}C-w _` <br />
`:vs[plit]` or `C-W_v` <br />
`C-W_t` <br />
`C-W_b` <br />

`qa[ll]` <br />
`wa[ll]` <br />

`tab sp[lit]` <br />
`tabo[nly]` <br />


## usr_10
大写的寄存器可以附加命令到对应小写的寄存器 <br />

`:[range]s[ubstitute]/{pattern}/{string}/[fags] [count]` <br />
[range] 空(当前行) or %(所有行) <br />

`&` 使用上一次的falg <br />
`c` 对于每次替换都确认 <br />
`e` 忽略错误，写脚本的时候用 <br />
`g` a occurrences, else first occurrence in each line <br />
`i` ignore case <br />
`I` NOT ignore case <br />
`n` report the number of matches, do NOT actuay substitute <br />
`p` Print the ine containing the ast substitute. <br />
`#` Like [p] and prepend the ine number. <br />
`l` Like [p] but print the text like `:list`. <br />
`r` 有点复杂 // TODO <br />

`sub-replace-expression` // TODO

啊啊啊，vim替换模式是真的强，但同时又很复杂

`global` mode // TODO


`[n]:`


`[range]r[ead] name`

`gUw` `guw` `g~~`

`!{motion}{program}` 用外部程序, 配合`r` `w` 太强大

`!!{filter}` 对当前行 <br />
`{Visual}!{filter}` <br />

`C-L`

这章太过于强大！！








vim: set noet:sw=4:
