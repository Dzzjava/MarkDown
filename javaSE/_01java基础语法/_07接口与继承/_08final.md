# final
> 在不同的地方,final 修饰后有不同的作用

| 修饰方 | 说明 | 注释 |
|---|---|---|
| 类 | 不能被继承 | 编译错误 |
| 方法 | 子类不能重写 | 编译错误 |
| 基本变量 | 只能赋值一次 | 赋值多次编译错误 |
| 引用 | 只能指向一次 | 指向多次编译错误 |

## 常量
> 可以公开,直接访问,不会变化的值

* 使用 ```public static final 类型 名称 = 值;```
> 一般名称使用大写,比如: 数学类的 圆周率 PI

# 练习 final

```text
尝试继承 String 类
```

## 答案

```text
因为 String 被 final 修饰
	不能继承
```