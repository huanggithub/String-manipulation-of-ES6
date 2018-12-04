# 常用操作
## 字符串比较
```
 let str = "string"; 
 // 查找字符串是否包含 , 第二个参数可以确认 起始位置 
 console.log('includes',str.includes("i")) // true 
 // 字符串是否以XXX开头
 console.log('start',str.startsWith('str')) // true
 // 字符串是否以XXX结尾  
 console.log('end',str.endsWith('ng')) // true
```
## 字符串复制
```
 // 字符串复制
 let re = 'co';
 console.log(re.repeat(2)) // coco 
```
## 字符串模板
```
let name = "list"; 
let info = "hello world"; 
let m = `i am ${name},${info}`; 
console.log(m) 
// 输出结果 
i am list,hello world 
```
## 长度补全es7草案
```
console.log('1'.padStart(2,'0'))   //第一个参数表明总长度，第二个参数表示需要在头部添加的字符串 小于原长度时不补全
//输出结果
01
```
