# To-do-list

## 项目介绍 INTRODUCE

本项目是基于 html+css+typescript 的练习小项目，实现了 todolist 中的常见功能。包括新增、删除、已完成等。
由于是主要学习 ts 的练习，函数中的类型写的很具体，在实际开发过程中可以使用类型推断的一些变量应该可以不用特意声明。

## 注意

### 怎样在浏览器中运行 ts

由于浏览器不直接支持 ts，所以需要将我们写的 ts 编译为 js 才可以使用。
创建 ts 文件后，可以使用`tsc`这个命令来将 ts 文件转换为 js 文件

### 每次修改后都要重新运行“tsc”命令转换

解决：使用`tsc -w`这个命令行可以监听到 ts 文件，只要 ts 文件重新保存，
就会自动将 ts 文件转换为 js 文件
