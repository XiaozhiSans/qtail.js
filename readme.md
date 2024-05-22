### qtail.js
[![npm publish status](https://github.com/XiaozhiSans/qtail.js/actions/workflows/npm-publish.yml/badge.svg)](#)

如何使用:  
#### 1.html
```html index.html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/XiaozhiSans/qtail.js/qtail.js"></script>
```


#### 2.npm
```bash
npm i XiaozhiSans/qtail.js
```


### 可用函数
```js functions.js
qtail.getVer(); // 在控制台输出 qtail.js 完整版本信息,并返回 qtail.js 版本号,示例返回值: "v1.6.1"
qtail.generation(name, tail); // 生成带有小尾巴的昵称,示例返回值: "name⁧tail⁦"
qtail.retail(tail); // 对尾巴进行重整,示例返回值: "tail"

/*
 * 过时函数
 * 它们曾经存在过,现在已被取代
 */
qtail.rstr(str); // 对字符串进行重整,示例返回值 "str"
```


### 扩展模块
+ [qtail.js html 模块](https://xiaozhisans.github.io/qtail/js/qtail.html.js)


## 协议
```txt LICENSE.txt
MIT License
 
Copyright (c) 2024 XiaozhiSans
 
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
 
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
 
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
