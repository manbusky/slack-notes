
### 移动, 跳转

- `h` 左移一个字符;
- `j` 下移一行;
- `k` 上移一行;
- `l` 右移一个字符;
- `w` 移到下一个单词起点; 
- `e` 移到单词的末尾处； 
- `b` 移到单词的起点；
- `3w` 相当于按 3 次 `w`；
- 成对出现的括号，例如：`{`、`[`、`(`，使用 `%` 跳至匹配位置；
- `0` 跳至行的起始位置；
- `$` 跳至行的末尾位置；
- `gg` 跳至文件的起始位置；
- `G` 跳文件最后一行的起始位置；
- 组合键：`3G`,跳至第三行的起始位置；

### find

- 查找当前行下一个或者上一个字符, 使用`f`和`F`，例如： `fq`；
- 组合键 `3fq`，往下查找第三个 `q`；
- 查找下一处当前光标下的单词，按`*`，查找上一处当前光标处的单词，按`#`；
- 在整个文件中查找使用 `/` 进入命令模式，输入字符串，按回车，即可以查找到，然后按 `n` 和 `N` 查找下一处或者上一处；

### edit

- 插入多次一样文本，使用组合键: `3igo` `Esc`，不需要按 3 次 go；
- 插入内容到一个新行，使用 `o` 或者 `O`，之后直接进入插入模式；
- `x` 和 `X` 删除当前位置的或者左边的一个字符；
- `r` 替换当前位置的一个字符，并且不切换到插入模式；
- `d` 删除命令，`dw` 删除当前光标右边的一个单词；`d2e`删除当前光标右边的两个单词；

### 其他

- 重复上一条命令，只需要按`.`；
- `u`键撤销，undo
- `ctrl + R`，redo


### 虚拟模式
- `v` 进入虚拟模式
- 跳转键，从当前位置开始选中内容；
- `d`，可以删除选中内容；


















