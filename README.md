# java-script
学习JS的进度
字符长度：”xxxxxxxxxxxxx”.length

可以直接计算：3+4         7

注释方法和java同：//

弹出选择是或取消的窗口：confirm('This is an example of using JS to create some interaction on a website. Click OK to continue!');

弹出输入框: prompt("What is your name?");

PS.空格也是字符哦

输出：console.log()

直接输出内容要加“”，直接计算显示结果则不用

比较的用法：

•	> Greater than

•	< Less than

•	<= Less than or equal to

•	>= Greater than or equal to

•	=== Equal to

•	!== Not equal to

if的用法：if(   ) {   } else {   }

显示字符串的部分："wonderful day".substring(3,7),显示derf,字符从0开始计

定义：var myage=20;

定义后的用法：var a=”xxxx”,a.length;a.sustring(,);

函数的使用

var divideByThree = function (number) {

    var val = number / 3;

    console.log(val);

};

divideByThree(12);

return用法

var nameString = function (name) {return "Hi, I am" + " " + name;};

可安排多个变量，全局变量在函数外定义，函数内优先使用局部变量。

调用函数是字符型变量要在括号内加“”；

Math.random()随机出一个0-1之间的数

for的用法

for(var i=1;i<10;i++){console.log(i)};

array

var names=["jane","micheal","ellen","betty","lll"];

for(var i=0;i<names.length;i++)

{console.log("I know someone called "+names[i])}


“\”符号可以用来换行
