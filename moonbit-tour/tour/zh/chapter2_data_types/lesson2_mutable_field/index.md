# 结构体的可变字段

结构体字段默认不可变，但可以通过在字段声明中使用`mut`关键字实现可变性。

在前面的课程中，我们已经了解 MoonBit 的集合类型可以通过类型声明中的`mut`关键字实现可变与不可变的控制。

示例中的`MutPoint`结构体包含两个字段：可变的`mx`和不可变的`y`。  
您可以通过重新赋值修改`mx`字段的值，但无法修改`y`字段的值。