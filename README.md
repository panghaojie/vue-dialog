# vue-dialog

> vue弹出窗口组件

## Build Setup

``` bash
# submit监听确定事件，width,height窗口初始大小，showWin显示隐藏窗口

import dialogEl from 'dialog'

<dialog-el :showWin.sync='show' @submit='submit' width='500' height='300'>
  <div slot='title'>标题</div>
  <div slot='content'>按住头部可拖拽、右下角放大缩小、可最大化</div>
</dialog-el>
```
## 预览

<a href="https://zhazhjie.github.io/vue-components-demo/?id=dialog">Demo</a>
