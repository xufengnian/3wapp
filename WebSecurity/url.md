---
title: "url"
date: 2016-03-13 15:32
---

# url

### url字符

* 1.特殊字符

    特殊字符url编码：一个百分号+对应字符的ASCII（16进制）码值

    * \+ (空格, %20)

    * / (分隔目录和子目录, %2F)

    * ? (分隔实际的URL和参数, %3F)

    * % (指定特殊字符, %25)

    * \# (表示书签, %23)

    * & (URL中指定的参数间的分隔符, %26)

    * = (URL中指定参数的值, %3D)

    * \ (目录路径, %5C)

    * . (句号, %2E)

    * : (冒号, %3A)

* 2.非法字符

    * 双字节字符（如汉字）

    * 空格

### 绕过

* # 绕过对 "某些后缀" 的限制

* %00 截断，绕过 ereg 等的过滤， 文件上传

### 参考

* [URL重定向/跳转漏洞][1]
* [URL Hacking - 前端猥琐流][2]

[1]: http://drops.wooyun.org/papers/58
[2]: http://drops.wooyun.org/tips/750
