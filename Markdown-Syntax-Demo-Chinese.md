# <center><font face="宋体" font color=LightCoral>Markdown syntax demo</font></center>
## <center><font face="楷体" size=5>Hello_Warden</font></center>

### 使用软件与环境搭建

1. **软件**：VisualStudio Code [官方下载地址](https://code.visualstudio.com/download)

2. **插件与扩展**：
   - Markdown Preview Enhanced
   - Markdown ALL in One
   - Paste Image

3. **环境**：Windows 11

### Markdown语法演示

1. 标题
要在标题前加入一个井号+一个空格+标题内容，最高有六级标题，示例：
   - 一级标题：`# 标题`
   - 二级标题：`## 标题`
   - 三级标题：`### 标题`
   - 四级标题：`#### 标题`
   - 五级标题：`##### 标题`
   - 六级标题：`###### 标题`

2. 段落
段落之间使用一个空行分隔，使用-+空格输入呈现，示例：
   - 第一段
   - 第二段
   - 第三段

3. 列表
   - **无序列表**：使用-+空格+内容输入呈现，示例：
     - 列表1
       - 列表1.1
       - 列表1.2
       - 列表1.3
     - 列表2
       - 列表2.1
       - 列表2.2
       - 列表2.3
   - **有序列表**：使用数字+空格+内容输入呈现，示例：
     1. 列表1
        1. 列表1.1
        2. 列表1.2
        3. 列表1.3
     2. 列表2
        1. 列表2.1
        2. 列表2.2
        3. 列表2.3
   - **TodoList**使用-+空格+[ ]+内容输入呈现，示例：
     - [ ] a
     - [x] b
     - [ ] c

4. 表格
   - **使用|+内容+|+内容+|+内容+|的输入方式呈现，示例：**
     | 姓名 | 年龄 | 成绩 |
     | :---: | :---: | :---: |
     | 张三 | 18 | 58 |
     | 李四 | 19 | 60 |
     | 王五 | 20 | 70 |
   - **对齐方式：输入与上方一样，不过第二行的英语冒号要减去相对方向，示例：**
     | 左对齐 | 居中 | 右对齐 |
     | :--- | :---: | ---: |
     | a | b | c |
     | d | e | f |
     | g | h | i |

5. 常见的Markdown语法符号
     | 示例 | 符号 |
     | :---: | :---: |
     | *斜体* | `* *` |
     | **粗体** | `** **` |
     | ***斜体加粗*** | `*** ***` |
     | ==高亮== | `== ==` |
     | ~~删除线~~ | `~~ ~~` |
     | <u>下划线</u> |``` <u> </u> ```|
     | ``` printf("Hello World");``` | 内容前后各加入``` |

6. 代码块
   ==***C***==
   ```C
   #include <stdio.h>
   int main(){
      printf("Hello, World!");
      return 0;
   }
   ```
   ==***Java***==
   ```Java
   public class HelloWord {
      public static viod main(String[] args){
         System.out.println("Hello, World!");
      }
   }
   ```

7. 分割线
   - 分割线：使用三个以上的-+空格+*+空格+_+空格输入呈现，示例：
     - ---
     - ***
     - ___

8. 图片与链接
   - 图片：使用!+[图片名称]+(图片地址)的输入方式呈现，支持jpg、png、gif、svg等格式，示例：
     - ![Eden](Images/131135880_p0.jpg)
   - 链接：使用[链接名称]+(链接地址)的输入方式呈现，示例：
     - [Eden](https://www.pixiv.net/artworks/131135880)
     - 也可以用这种方式添加[链接](用英语输入法打出方括号，前一个方括号写入链接名称，后一个括号写入链接脚注，或者在文件夹里添加文件，作为导航的方式引导至该文件。)

9.  引用
    - 引用：使用>输入方式呈现，每增加一个>会在画面上增加一个下一级，示例：
      > OpenJDK: https://openjdk.org/
      > FreeCAD: https://github.com/FreeCAD/FreeCAD/
      > ESP32-DIV: https://github.com/cifertech/ESP32-DIV/
      >>WIKI: Welcome to the official Wiki for ESP32-DIV, a powerful open-source multi-band wireless toolkit built on the ESP32 microcontroller! Designed for wireless testing, signal analysis, and protocol exploration, the ESP32-DIV supports Wi-Fi, Bluetooth Low Energy (BLE), 2.4GHz, and Sub-GHz frequencies. Whether you're a cybersecurity enthusiast, a wireless tech hobbyist, or an IoT developer, this project offers a versatile platform for your experiments.
      >>>⚠️ Disclaimer: This project is for educational and research purposes only. Do not use it for malicious activities or unauthorized access.

10.  脚注
    - 脚注：使用`[^1]+(脚注内容)`的输入方式呈现，在程序最下放写上脚注来源即可，示例：
    - 这里有一个脚注[^1]，大家可以看看。

### 数学公式

1. 行内公式：使用`$+公式内容+$`，示例：
   三相电功率计算公式
    - $P=√3*U*I*cos(φ)$

2. 行间公式：使用`$$+公式内容+$$`，示例：
   输入电流有效值为IRMS
    - $$IRMS=\frac{Po}{η*umin*cosφ}$$

3. 表格结合公式：
   | <font face="仿宋" font color=orange>公式</fant> | <font face="仿宋" font color=green>领域</fant> |
   | :---: | :---: |
   | $P=√3*U*I*cos(φ)$ | 三相电功率计算公式 |
   | $$IRMS=\frac{Po}{η*umin*cosφ}$$ | 输入电流有效值为IRMS |


[^1]: (https://baike.baidu.com/item/%E8%85%B3%E8%A8%BB/17821082)