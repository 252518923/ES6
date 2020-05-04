# 1.let
ES6新增了let命令，用来生命变量。它的用法类似于var,但是所声明的变量,只在let命令所在的代码块内有效。
    for (let i = 0; i < 10; i++) {
 }
    console.log(i) //ReferenceError: i is not defined<br><br>for(var i=0;i<10;i++){<br><br>}<br>console.log(i) //10<br>
