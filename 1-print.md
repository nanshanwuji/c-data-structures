## 引言

如果一个人有志于成为计算机大牛，c语言和数据结构是绕不过去的。本课程带大家一边学C语言，一边学数据结构。

## Linux命令行介绍
为了保持简单，我们直接用命令行教学。命令行是用来指使操作系统干活的工具，在命令行世界，你就是大爷，各种工具都是你的奴仆。但是我们要当一个聪明的大爷，因为工具都是死脑筋，只能按照你的指令行事。

当我们写好C语言的源文件时，用gcc编译器编译出可执行文件，命令如下
```c
// gcc是编译器命令，后面接的是命令行选项
// -o task1 表明生成的可执行文件名叫 task1, o是output的意思
// task.cpp 是源代码文件
gcc -o task1 task1.cpp
```

## Task1 - Hello World
下面请大家编写著名的hello-world程序，并编译执行
代码可以用sublime text或者nodepad等简单的代码编辑器编写，取名task1.cpp
```c
#include <stdio.h>
int main(int argc, char** argv)
{
    printf("hello world\n");
    return 0;
}
```
 


