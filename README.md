time_counter
============

Swift 计时器成果展示


# 教程地址

http://swiftist.org/topics/96?page=2#36

# 成果展示

ID|项目介绍|进度
---|---|---
（示例）[numbbbbb](http://github.com/numbbbbb/swift-2048)|完全按照教程进行|完成第一课内容
（示例）[lifedim](http://github.com/lifedim/swift-2048)|在教程基础上扩展了记录比分功能|全部完成

# 遇到问题？

如果在实践过程中遇到问题，你可以：

* 在群里询问(**Swift 兴趣交流二群：305014012**)
* 在[Swiftist](http://www.swiftist.org)发帖提问

大牛们会帮你解决的。

# 如何加入？

* 首先确保已经加群，如果还没加群，请加入**Swift 兴趣交流二群：305014012**
* 如果要展示自己的信息和进度，可以直接pr修改README或者发issue，我们会每天处理issue，将你的信息添加到README中
* 请保证展示内容真实，我们会进行检查，如果不符会进行删除

# 想被推荐？

我们会不定期推荐一些优秀的项目，如果想得到推荐，你可以：

* 在教程的基础上进行扩展，添加更多的功能，即使只是一个非常简单的功能，只要用心去做也会得到推荐
* 自己写教程，给大家用
* 分享自己的学习心得

# 如何pr

1. 首先fork此项目
2. 把fork过去的项目clone到本地
3. 在命令行运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/Swiftist/time_counter.git` 把我的库添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream master` 拉取此库的更新到本地
8. 运行 `git rebase upstream/master` 将更新合并到你的分支
