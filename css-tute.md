<!--
 * @Date: 2024-04-17 11:03:09
 * @LastEditors: ThetisEliza wxf199601@gmail.com
 * @LastEditTime: 2024-04-18 11:56:41
 * @FilePath: \vue-tute\css-tute.md
-->
## css 基础

### css语法
```css
h1      {color:red; font-size:14px;}
选择器  声明块
```
#### 选择器
- 简单选择器
  - 元素: p/h1/body
  - id: #para1 $\rightarrow$ `<p id=para1>`
  - 类：.vue-button $\rightarrow$ `<button class="vue-button">`
    - 类+元素 组合
  - 多个类
- 通用选择器：
  - *
- 分组选择器
  - 用`,`隔开
  - ```css 
    h1, h2, p {
    text-align: center;
    color: red;
    }
- 组合器 :hammer:
- 伪类 :hammer:
- 伪元素 :hammer:
- 属性 :hammer:

#### 引入方式
- 外部
  - ```html
    <head>
        <link rel="stylesheet" type="text/css" href='style.css'>
    </head>
- 内部
  - style标签
- 行内
  - style属性
- 冲突
  - 谁最后定义，选择谁

#### 注释
```css
/* 这是
一条多行的
注释 */ 

p {
  color: red;
}
```

#### Color
- 元素属性
  - background-color
  - color
  - border
- 颜色类型
  - rgb
  - hex
  - hsl

#### background
- 不透明度
  - opacity
  - rgba
- 图像
  - repeat：
    - 重复 X/Y轴
  - position：
    - 指定位置
- attachment
  - 背景固定/滚动
- 简写：
  - ```css
    body {
    background: #ffffff url("tree.png") no-repeat right top;
    }

#### 边框
- 注意简写属性的规则
  - ``` css
    p {
    border-top-style: dotted;
    border-right-style: solid;
    border-bottom-style: dotted;
    border-left-style: solid;
    } 
  - ``` css
    p {
    border-style: dotted solid;
    }
- 圆角：border-radius: 5px;
  
#### 边距
##### 外边距
- 外边距合并
  - 上下边距取最大，但是不为和
  - 内外边距取最大（外部元素没有内容的情况下），但是不为和
##### 内边距
  - 背景填充区域

#### 盒模型
- margin 外边距
- border 边界
- padding 内边距
- size

#### 轮框
- outline 在边框外
- width
- style
- color
- offset

### 字体
### 图标
### 列表
### 表格

## CSS 中级教程
### Display
- display：
  - none：不显示
  - inline：不换行
  - block：换行
- visibility：
  - hidden
  - visible
  - inherit
### Max-width
- 可根据实际情况缩小
### 定位
- Position
  - static：正常
  - relative：添加方向在正常上进行便宜
  - fixed：不随页面滚动变化
  - absolutely：相对于父组件绝对
  - sticky：滚动到头停在滚动边缘
  - z-index：堆叠顺序，越小越在下边
### Overflow

