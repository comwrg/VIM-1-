# My Vim Docs
创建这个repo是为了我使用Vim再上一个层次 <br />
我的想法是这个的，把一些Vim文档中个人觉得非常实用的东西但自己又不会的分类整理在这里 <br />
然后呢，平时使用Vim的时候顺带用上，什么时候觉得自己会了，就把那条命令删掉 <br />

## jumps, marks (from usr_03)
`CTRL-O`		Go to [count] Older cursor position in jump list <br />
`CTRL-I`		Go to [count] newer cursor position in jump list <br />
`:ju[mps]`		Print the jump list <br />
`:cle[arjumps]`	Clear the jump list of the current window <br />
`''`			可以在两个位置来回跳 <br />
`m'`			可以把现在这个位置加入jump list <br />

另外跳行操作`:n`和`nG`(这个n代表你要跳到哪一行) <br />
只有`nG`会把将原来的位置加入jump list <br /> 

`'"`			跳到上次编辑退出时候的光标位置 <br />
`'[`			最后一次进入编辑模式的地方 <br />
`']`			最后一次退出编辑模式的地方 <br />










vim: set noet:
