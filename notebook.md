# C language programming

## 1. 程序设计与C语言

人：what to do

计算机：how to do

计算机的语言使用十六进制

 辗转相除法：寻找最大公约数

```c
int u = 32;
int v = 26;
while (v!=0){
    int temp = u%v;
    u = v;
    v = temp;
}

printf("%d",u)
```

程序的执行

解释：让借助程序理解你的程序，有特殊的计算能力

编译：将程序翻译成计算机能懂的语言，有确定的运算性能、

面向对象的语言：类库

C语言：函数库

it was the summer of 1969

win: dev c++

mac: vscode



mac上用vim 直接vi+文件名



## 2. 计算

```c
#include <stdio.h>

int main() {
	int price = 0; // 定义了一个变量，保存数据的地方
	printf("请输入金额（元）");
	scanf("%d", &price);
	int change = 100 - price;
	printf("找您%d元\n", change);
	return 0;
}
```













