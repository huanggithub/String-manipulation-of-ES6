# 常用操作
## 字符串比较
```
 let str = "string"; 
 // 查找字符串是否包含 , 第二个参数可以确认 起始位置 
 console.log('includes',str.includes("i")) 
 // 字符串 是否以 str 开头 
 console.log('start',str.startsWith('str')) 
 // 字符串 是否 以 ng 结尾 
 console.log('end',str.endsWith('ng')) 
```
## 字符串复制
```
 // 字符串复制
 console.log(str.repeat(2))
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
console.log('1'.padStart(2,'0'))
//输出结果
01
```
