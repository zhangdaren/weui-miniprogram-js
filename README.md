# weui JS版本
由于在转换使用weui组件的小程序时，一般都是使用npm引入weui。

加上weui是由TS写成，因此npm包里的代码，其实是由webpack包装成的js版，并不是纯js版。

这对于想要将weui项目转换为uniapp带来一定的困扰，特制作weui纯js版，以方便转换~

# 食用方法
   
1. 备份原有项目：防止破坏原有项目
   
2. 替换weui为纯js版： 复制weui-miniprogram里所有内容，替换项目中相应目录及文件
   
3. 继续转换
