# <center><font face="宋体" color=LightCoral>Markdown syntax demo</font></center>
## <center><font face="楷体" size=5>Hello_Warden</font></center>

### Software and Environment Setup
1. **Software**: Visual Studio Code [Official Download](https://code.visualstudio.com/download)
2. **Extensions**:
   - Markdown Preview Enhanced
   - Markdown ALL in One
   - Paste Image
3. **Environment**: Windows 11

### Markdown Syntax Demonstration

1. Headers
Use hash symbols + space + content, with six levels available:
- Level 1: `# Header`
- Level 2: `## Header`
- Level 3: `### Header`
- Level 4: `#### Header`
- Level 5: `##### Header`
- Level 6: `###### Header`

2. Paragraphs
Separate paragraphs with blank lines, using `-` + space:
- First paragraph
- Second paragraph
- Third paragraph

3. Lists
- **Unordered lists**: Use `-` + space + content:
  - List1
    - List1.1
    - List1.2
    - List1.3
  - List2
    - List2.1
    - List2.2
    - List2.3

- **Ordered lists**: Use numbers + space + content:
  1. List1
     1. List1.1
     2. List1.2
     3. List1.3
  2. List2
     1. List2.1
     2. List2.2
     3. List2.3

- **TodoList**: Use `-` + space + `[ ]` + content:
  - [ ] a
  - [x] b
  - [ ] c

4. Tables
- **Basic table**:
  | Name | Age | Score |
  | :---: | :---: | :---: |
  | Zhang | 18 | 58 |
  | Li | 19 | 60 |
  | Wang | 20 | 70 |

- **Alignment**:
  | Left | Center | Right |
  | :--- | :---: | ---: |
  | a | b | c |
  | d | e | f |
  | g | h | i |

5. Common Markdown Syntax
| Example | Syntax |
| :---: | :---: |
| *Italic* | `* *` |
| **Bold** | `** **` |
| ***Bold Italic*** | `*** ***` |
| ==Highlight== | `== ==` |
| ~~Strikethrough~~ | `~~ ~~` |
| <u>Underline</u> | `<u> </u>` |
| ```printf("Hello World");``` | Triple backticks |

6. Code Blocks
- ==***C***==:
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
7. Horizontal Rules
   - Use three or more -, * or _:
     - ---
     - ***
     - ___
8. Images and Links
   - Images: ![Alt text](image path)
   - Example:
     - ![Eden](Images/131135880_p0.jpg)
   - Links:
     - [Eden](https://www.pixiv.net/artworks/131135880)
     - Alternative format: [link_name](hyperlink_footnote)
9.  Blockquotes
    - Example:
      > OpenJDK: https://openjdk.org/
      > FreeCAD: https://github.com/FreeCAD/FreeCAD/
      > ESP32-DIV: https://github.com/cifertech/ESP32-DIV/
      >>WIKI: Welcome to the official Wiki for ESP32-DIV, a powerful open-source multi-band wireless toolkit built on the ESP32 microcontroller! Designed for wireless testing, signal analysis, and protocol exploration, the ESP32-DIV supports Wi-Fi, Bluetooth Low Energy (BLE), 2.4GHz, and Sub-GHz frequencies. Whether you're a cybersecurity enthusiast, a wireless tech hobbyist, or an IoT developer, this project offers a versatile platform for your experiments.
      >>>⚠️ Disclaimer: This project is for educational and research purposes only. Do not use it for malicious activities or unauthorized access.
4.  Footnotes
    - Here's a footnote[^1] reference.
### Mathematical Formulas
1. Inline: $formula$
   Three-phase power formula:
    - $P=√3*U*I*cos(φ)$
2. Block: $$formula$$
   IRMS current calculation:
    - $$IRMS=\frac{Po}{η*umin*cosφ}$$
3. Formulas in Tables:
   | <font face="仿宋" font color=orange>Formula</fant> | <font face="仿宋" font color=green>Field</fant> |
   | :---: | :---: |
   | $P=√3*U*I*cos(φ)$ | Three-phase power formula |
   | $$IRMS=\frac{Po}{η*umin*cosφ}$$ | IRMS current calculation |


[^1]: (https://www.scribbr.com/citing-sources/what-are-footnotes/)