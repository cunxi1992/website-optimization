### 如何打开文件:
1.用Google浏览器打开index.html
2.用Google浏览器打开pizza.html

### 优化index.html
1.去除外联css
2.将所有的js代码加上async属性
3.图片本地化
4.124行，将js文件本地化
5.将所有js内容移至html末尾

### 优化views/js/main.js
1.将css文件以及js文件放到html的末尾
2.修正changePizzaSizes，解决dom重复性选择问题
3.修正updatePositions，将layout的提取放在循环前面
4.在第486行将dom的操作放在循环之外
5.在第521行将layout的相关计算放在循环之外以防止重复计算
6.在第551行删除var，防止多次声明

