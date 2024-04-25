### qtail.js
  
如何使用:  
#### 1.html
```html
<!-- 任选其一 -->
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/XiaozhiSans/qtail.js/qtail.js"></script>
<script type="text/javascript" src="https://xiaozhisans.github.io/qtail/js/qtail.js"></script>
<script type="text/javascript" src="https://raw.githubusercontent.com/XiaozhiSans/qtail.js/main/qtail.js"></script>
```  
#### 2.npm
```bat
npm i XiaozhiSans/qtail.js
```  
  
### 可用函数
```js
qtail.getVer(); // 在控制台输出 qtail.js 完整信息,并返回 qtail.js 版本号,示例返回值: "v1.6.1"
qtail.generation(name, tail); // 生成带有小尾巴的昵称,示例返回值: "name⁧tail⁦"
qtail.rstr(str); // 对字符串进行重整,示例返回值: "str"
```  
  
### 扩展模块
+ qtail.js html 模块:
  - 引入 html:
  > **注**:你可以通过[qtailLoader](https://github.com/XiaozhiSans/qtailLoader)实现自动化加载.
    ```html
    <!-- 任选其一 -->
    <script type="text/javascript" src="https://cdn.jsdelivr.net/gh/XiaozhiSans/qtail/js/qtail.html.js"></script>
    <script type="text/javascript" src="https://xiaozhisans.github.io/qtail/js/qtail.html.js"></script>
    <script type="text/javascript" src="https://raw.githubusercontent.com/XiaozhiSans/qtail/main/js/qtail.html.js"></script>
    ```  
  - 热键说明:
    1. 回车(Enter): 执行函数 `qtailHtml.main();`
    2. 退出(Esc): 执行函数 `qtailHtml.exit();`
    3. 8号功能键(F8): 执行函数 `qtailHtml.copy();`
  
  - 可用函数:
  ```js
  qtailHtml.main(); // 从 html 页面拉取 "#qtail" 表单的内容并调用 qtail.generation(); 生成昵称并返回 html 页面带有 "#result" 的元素
  qtailHtml.copy(); // 将 html 页面上带有 "#result" 的元素的内容复制到剪贴板
  qtailHtml.share(); // 分享页面
  qtailHtml.donation(); // 喜欢页面
  qtailHtml.exit(); // 询问是否要退出页面
  ```  
  
## 协议
```
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
  