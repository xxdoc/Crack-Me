# Crack-Me
很久之前群里兴起一股破解风，然后我用VB6写了这个“来破解呀”。现在也发上来吧233

实际上技术含量不高，在那些真正的大神写的CrackMe之前真的算不上什么

重在分享嘛233

`【慎入】`

`内有粗鄙之语！`

`代码极其暴力！`

# 一些细节

- 函数名用了难听的粗口命名，一反编译就看到满屏脏话
- 瞎引用了一堆API，即使用VB Decompiler反编译了也看不出到底用了那个API
- 字符串全部通过数学方式“加密”，直接查看字符串是看不出来的
- 数值经过加密，每次更改的时候都会更改存储的位置
- 有个Timer检测系统时间，如果程序被挂起了一秒或以上（说明程序可能正在被调试）就触发异常
- 弄了个资源文件，如果用ResHacker之类的程序能看到个小彩蛋
- 附上了用来生成粗口代码的生成器和生成“加密”字符串的生成器
