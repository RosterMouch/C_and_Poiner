- 错误地对一个未初始化的变量进行解引用
- 错误地对一个NULL(nullptr)指针进行解引用
- 像函数错误地传递NULL指针
- 未检测到指针表达式的错误，从而导致不可预测的结果
- 对一个指针进行减法运算，使它非法地指向了数组第一个元素的前面的内存位置
- 一个值应该只具有一种意思
- 如果指针并不指向任何有意义的东西，就把它设置为NULL。