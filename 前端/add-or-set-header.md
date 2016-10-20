---
title: response setHeader与addHeader的区别
---
- setHeader(name, value)：如果Header中没有定义则添加，如果已定义则用新的value覆盖原用value值。
- addHeader(name, value)：如果Header中没有定义则添加，如果已定义则保持原有value不改变。
<!--more-->