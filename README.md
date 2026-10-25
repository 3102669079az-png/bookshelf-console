# 书架管理程序

一个 Java 控制台程序，练习面向对象与文件持久化。

## 功能

- 添加书籍（书名 / 价格 / 页数，带输入校验）
- 列出全部书籍
- 按书名查找
- 按书名删除
- 数据保存在 `shelf.txt`，重启后自动恢复

## 技术点

- 抽象类与继承：`Book` → `PaperBook` / `EBook`
- 接口：`Downloadable`
- 自定义异常：`BookException`
- 集合：`ArrayList`
- 输入交互：`Scanner`
- 文件读写：`java.nio.file.Files`

## 运行

需要 JDK 17，直接在 IDEA 里运行 `Main.main()`。
