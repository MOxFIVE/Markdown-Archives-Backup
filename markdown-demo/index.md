title: markdown-demo
comments: false
date: 2016-01-17 22:48:52
fancybox:
---

这是 *斜体*，这是 **粗体**，这是~~删除线~~

# 这是一个一级标题 h1

## 这是一个二级标题 h2

### 这是一个三级标题 h3

#### 这是一个四级标题 h4

##### 这是一个五级标题 h5

###### 这是一个六级标题 h6

- 无序列表项 一
- 无序列表项 二
- 无序列表项 三
    - 次级无序列表项
    - 次级无序列表项
        - 次级无序列表项
        - 次级无序列表项

> 汉皇重色思倾国，御宇多年求不得。杨家有女初长成，养在深闺人未识。
天生丽质难自弃，一朝选在君王侧。回眸一笑百媚生，六宫粉黛无颜色。

1. 有序列表项 一
1. 有序列表项 二
1. 有序列表项 三
    1. 次级有序列表项
    1. 次级有序列表项
        1. 次级有序列表项
        1. 次级有序列表项

> 长恨歌 — 白居易
>> ……
临别殷勤重寄词，词中有誓两心知。七月七日长生殿，夜半无人私语时。
在天愿作比翼鸟，在地愿为连理枝。天长地久有时尽，此恨绵绵无绝期。


`inline code 行内高亮`

-|SoftwareName|　　Developer　　|Mac|Win|Free|　　　　Note　　　　
:-:|-|-|:-:|:-:|:-:|-
1|[GitHub Desktop](https://desktop.github.com/)|[GitHub, Inc.](https://en.wikipedia.org/wiki/GitHub)|√|||GitHub 桌面版
2|[Sublime Text 3](http://www.sublimetext.com/)|[Jon Skinner](https://en.wikipedia.org/wiki/Sublime_Text)||√|—|代码编辑器
3|[Brackets](http://brackets.io/)|[Adobe Systems](http://is.gd/q5bGeJ)|√|||Web 代码编辑器
4|[Dash](https://kapeli.com/dash)|[Kapeli](https://kapeli.com/)|√|—|x|API Snippet 代码管理

    这是一个代码块，此行左侧有四个不可见的空格。

```
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
```

