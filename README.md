# 说明
这是一个vue轮子的库
[![Build Status](https://travis-ci.org/helloyongwei/lunzi-vue.svg?branch=master)](https://travis-ci.org/helloyongwei/lunzi-vue)

## 介绍
这是我在学习vue过程中做的组件库.

## 安装
1. 设置css
```css
*,
*::before, 
*::after {
  box-sizing: border-box;
}

```

```css
html {
      --button-height: 32px;
      --font-size: 14px;
      --button-bg: white;
      --button-active-bg: #eee;
      --border-radius: 4px;
      --color: #333;
      --border-color: #999;
      --border-color-hover: #666;
    }
```

2. 安装
```
npm i -S lunzi-vue
```

3. 引入lunzi-vue
```
import {Button, ButtonGroup, Icon} from 'lunzi-vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    'g-button': Button,
    'g-icon': Icon
  }
}
```

