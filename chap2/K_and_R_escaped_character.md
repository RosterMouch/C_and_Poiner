# K&R C转义符集合
下面的转义符中，有些进行了特殊标记，表示它由`ANSI C`标准中新增的。在K&R C中并未实现。
- **`\a`**：警告字符。它将走向终端铃声或产生其他一些可听见或可看见的信号
- `\b`：退格符
- `\f`：进纸字符
- `\n`：换行符
- `\r`：回车符
- `\t`：水平制表符
- **`\v`**：垂直制表符
- `\ddd`：ddd表示1~3个八进制数字。这个转义符表示的字符就是你给定的八进制数值所代表的字符。
- **`\xddd`**：与上例类似，只是八进制数换成了十六进制数。

### 注意，任何十六进制数都有可能包含在\xddd序列中，但如果结果值得大小超出了表示字符的范围，其结果就是未定义的。