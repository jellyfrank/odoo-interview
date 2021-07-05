# Odoo 面试 参考题

## 基础

1. Model和TransientModel区别是什么？什么场景下应该使用TransientModel?

2. 字段的compute属性是用来做什么的？如何将包含compute属性的字段的值存储到数据库中？

3. 如何创建一个索引字段？

4. 如何设置一个字段的默认值？默认值可以是一个函数吗？

5. 如何给限定某个字段只能由某个让用户组的人访问？

6. 如何将某个字段设置为提权访问(admin)?



## 中级

1. 什么是开发者模式？开发者模式中的三种模式的区别是什么？

2. models中inherit和inherits的区别是什么？

3. Binary字段与附件对象有什么关系？如何更改附件默认存储的位置？

4. base模块和web模块分别在系统中扮演什么样的角色？

5. 如何将自定义的widget添加到系统中？

6. csrf_token是什么？有什么作用？是如何生成的？

7. 为什么jsonrpc中不用传csrf_token?

8. Session是如何存储的？odoo是如何判断Session是否有效的？

9. 配置文件中的limit_memory_soft和limit_memory_hard区别是什么？

10. 如何更新系统中全部的模块？其原理是怎样的？

## 高级

1. Environment对象的作用是什么？

2. odoo默认的Registry的LRU大小是多少？

3. odoo的多workder模式如何开启？单worker和多worker的运行机制有什么不同？