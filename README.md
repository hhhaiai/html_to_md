# 说明

## 项目连接

1.码云:https://gitee.com/pythonywy/html_to_md 

2.github:https://github.com/a568972484/html_to_md

## 功能介绍

需要安装的python模块

`pip3 install requests`

`pip3 install lxml`

`pip3 install beautifulsoup4`

代码以更新可以运行`Crawl_blog_post_6.1.py`,可以运行`visual.exe`,exe文件就不用安装依赖

- 功能一：批量爬取博客园首页的所有随笔字典并保存JSON文件，且随笔全部转成MD格式文件
- 功能二：输入指定随笔网址把随笔内容转成MD并且保存
- 功能三：爬取某个分目录下博客
- 功能四:  按照分类爬取分类下所有博客,内容添加hexo传输内容包括标题,日期,方便个人博客搭建

由于不同博客具有不同的见状性`要根据博客能让进行适当的修改就可以使用此程序

程序没有加入`多进程`与`多线程`进去增加博客园的负担

爬取内容`请不要用做商业用途`

初衷`主要是为了帮助博主把已上传的随笔下载至本地方便修改`

# 更新日志

`2019.7.20`

增加了功能

功能介绍:爬取某个分目录下博客

版本升级至5.0,增加了可视化界面可视化界面exe程序,增加了见状性,

只需下载exe运行即可

温馨提示:

程序由可能会被流氓杀毒软件屏蔽请自行恢复

绝对无毒的,没有添加任何恶意信息

运行程序第一功能和第三功能会因为博客数量多出现卡顿,由于本人对程序理解还不深刻没能找到解决办法,请大家见谅请不要关闭程序,结束后会自动出现数据的

都是自学的一些模块可能会有点理解不到位请大家见谅,需要原代码的解压密码私聊我就好了.

核心代码在'core_code.py'中注释都加全了

`2019.8.21`

增加了功能

功能介绍:按照分类爬取分类下所有博客,内容添加hexo传输内容包括标题,日期,方便个人博客搭建

exe文件没有更新,更新了核心文件

修复了:无法获取博客内容

md文本内容匹配更加规范,内容更加完善

`2019.9.2`

版本更新至6.1

- 修正了匹配规则
- 修正了li与ul标签
- 修正了```格式
- 修正了最后一行会出现宫格
- 我将可视化界面代码全部展示了,但是版本还是5.版本的

`2019.10.16`

- 生成可视化解码

`2019.10.18`

- 修正批量爬取文件标题匹配不到倒bug修正匹配格式
- exe文件还未`更新`,py程序已更新

# 再次强调

`该程序只为了帮助学习`

码云名称:YWY

码云链接:https://gitee.com/pythonywy

github_id:a568972484

github_url:https://github.com/a568972484

作者博客:小小咸鱼ywy

博客链接:`https://www.cnblogs.com/pythonywy

`希望得到大家相关体验,好进行后续的改进,谢谢`


