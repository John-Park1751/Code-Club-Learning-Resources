## 亮闪闪的星星

让我们通过循环的组合来创造一颗闪亮的星星。

--- task --- 在你的动画中添加一个'岩石'精灵。

![添加星星角色](images/space-star-sprite.png)

--- /task ---

--- task --- 你能为你的星形精灵添加代码，让星星反复增长和缩小吗？

![测试闪亮的星星](images/sprite-star.png)

--- hints ---
 --- hint --- 当绿 **旗被点击** 时，星星应该 **放大** 一段时间，然后 **缩小** 一段时间。 它应该这样做，以便它变得更大，然后永远变小 看起来像是闪亮的光芒。 --- /hint--- ---hint--- 以下是您需要的代码块：

```blocks3
重复执行 (10) 次

当 ⚑ 被点击

将大小增加 (10)

将大小增加 (10)

重复执行

重复执行 (10) 次
```

--- /hint --- --- hint --- 这是让你的星星放大和缩小的代码： ![星星精灵](images/sprite-star.png)

```blocks3
当 ⚑ 被点击
重复执行 
  重复执行 (20) 次 
    将大小增加 (2)
  结束
  重复执行 (20) 次 
    将大小增加 (-2)
  结束
```

--- /hint --- --- /hints --- --- /task ---