---
title: _blank漏洞
---
当以
```html
<a href="http://blog.baungo.com" target="_blank">link</a>
```
打开新的页面时，在目标页面内使用
```javascript
window.opener.location = 'http://baungo.com';
```
即可使源页面自动跳转。[参考文章](https://zhuanlan.zhihu.com/p/22231471)
<!--more-->