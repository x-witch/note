### 选择器
1. 元素选择器
2. id选择器(#id)
3. class选择器(.class)
4. 属性选择器([属性名/属性名=值])
> 根据属性名和属性值选中元素
5. 通用选择器(*)
6. 伪类选择器(:伪类名称,冒号前面可以指定元素或类)
```
根据某些元素的某种状态  
:link 超链接未访问时的状态  
:visited 超链接访问过后的状态  
:hover 鼠标悬停状态  
:active 激活状态，鼠标按下状态  
顺序遵循爱恨法则:love hate
```
7. 伪元素选择器(::before/after)  
> 选择一个元素的某个部分而不是元素自己
> 如span::before{content:"《"}

### 选择器组合
1. 并且 如 span::before
2. 后代元素  空格
3. 子元素 >
4. 相邻兄弟元素 +
5. 兄弟元素 ~

### css书写顺序
1. 位置属性（position,top,right,z-index,display,float等）
2. 大小（width,height,padding,margin）
3. 文字系列（font,line-height,letter-spacing,color-text-align等）
4. 背景（background,border等）
5. 其他（animation,transition等）

[前端书写规范](https://guide.aotu.io)
