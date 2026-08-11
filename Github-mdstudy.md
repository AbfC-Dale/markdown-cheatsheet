# 一级标题
## 二级标题
### 三级标题
 *斜体* _斜体_

`*内容*`、`_内容_`

 **加粗** __加粗__
 
 `**内容**`、`__内容__`

 ***斜体加粗*** ___斜体加粗___

  `***内容***`、`___内容___`

 ~~加删除线~~

`~~内容~~`
## 网址
[bilibili](https://www.bilibili.com/)
```
[bilibili](https://www.bilibili.com/)
```
https://www.bilibili.com/
```
https://www.bilibili.com/
```
<https://www.bilibili.com/>
```
<https://www.bilibili.com/>
```
## 跳转
[link to heading](#一级标题)
```
[link to heading](#一级标题)
```
[link to top](#top)
```
[link to top](#top)
```
## 表格
**自动忽略空格**

**默认左对齐**
左对齐 | 右对齐 | 居中
| :--- | ---: | :---:
打出\| | 字 | 字 
字     | 字 | 字

First Header  | Second Header
------------- | ------------
Content Cell  | Content Cell
Content Cell  | Content Cell
*"\|"两边至少有一个"-"*

## Code
### Inline code(可以用来突出关键词)
`code()`

### Code block
**首行"```+代码块的语言"点亮文字，否则为灰色**
```javascript
var myGreatVariable = 'test'
```

```
666
```

```python
print(11)
```

## List
* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

```
* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2
```

```
- Bullet list
    - Nested bullet
        - Sub-nested bullet etc
- Bullet list item 2 
```

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

```
1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered
```

*可以自动编号*

```
1. A numbered list
    1. A nested numbered list
    1. Which is numbered
1. Which is numbered
```
- [ ] An uncompleted task
- [x] A completed task
    - [ ] A subtask

```
- [ ] An uncompleted task
- [x] A completed task
    - [ ] A subtask
```
## Quoting
> Blockquote
>> Nested Blockquote

```
> Blockquote
>> Nested Blockquote
```

**脚注**在vscode上不能编译，可以在github试试


Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, Add a carriage return and prefix the new line with 4 spaces.

    This is a second line.

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, Add a carriage return and prefix the new line with 4 spaces.

    This is a second line.
```

## Media/Emojis
**依旧vscode不行，可以用github**
![picture alt](https://placehold.co/600x200 "Title is optional")

```
![picture alt](https://placehold.co/600x200 "Title is optional")
```

Emoji（表情符号符号应该出现在冒号之间）

```
:+1: :exclamation:
```

Enhance your markdown[Emoji Cheat Sheet]（https://www.webfx.com/tools/emoji-cheat-sheet/）

## Alerts
**在github上**
> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.

## 杂项
折叠文本

<details>
    <summary>豆豆</summary>
    <p>一个爱哭小鬼，一个傻瓜</p>
</details>
