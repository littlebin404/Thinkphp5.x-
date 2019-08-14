1.以带有漏洞的thinkphp版本为验证对象。工具测试结果如下：
![iamge](https://github.com/littlebin404/Thinkphp5.x-/blob/master/images/1.png)
![iamge](https://github.com/littlebin404/Thinkphp5.x-/blob/master/images/2.png)


用菜刀进行连接：
![iamge](https://github.com/littlebin404/Thinkphp5.x-/blob/master/images/3.png)
验证成功！

Thinkphp v5.0.x补丁地址: https://github.com/top-think/framework/commit/b797d72352e6b4eb0e11b6bc2a2ef25907b7756f
Thinkphp v5.1.x补丁地址: https://github.com/top-think/framework/commit/802f284bec821a608e7543d91126abc5901b2815

整个thinkphp框架里对控制器没有进行严格的过滤与查找，使攻击者可以伪造恶意参数进行插入，原因是过滤的正则表达式没有正确使用，导致可以绕过。
