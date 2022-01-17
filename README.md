# how2install-brew

https://zhuanlan.zhihu.com/p/111014448

首发于
MAC专区
无障碍
写文章
登录
Homebrew国内如何自动安装（国内地址）
Homebrew国内如何自动安装（国内地址）
金牛肖马
金牛肖马
知行合一
3,700 人赞同了该文章
如果你是提示来这个页面查看错误，说明你用的脚本太老了，用下面脚本安装。
自动脚本(全部国内地址)（在终端中复制粘贴回车下面脚本)


苹果电脑 常规安装脚本（推荐 完全体 几分钟安装完成）：

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
苹果电脑 极速安装脚本（精简版 几秒钟安装完成）：

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)" speed
苹果电脑 卸载脚本：

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh)"
常见错误去下方地址查看

https://gitee.com/cunkai/HomebrewCN/blob/master/error.md

Linux电脑 安装脚本：

rm Homebrew.sh ; wget https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh ; bash Homebrew.sh
Linux电脑 卸载脚本：

rm HomebrewUninstall.sh ; wget https://gitee.com/cunkai/HomebrewCN/raw/master/HomebrewUninstall.sh ; bash HomebrewUninstall.sh
编辑于 2021-09-12 13:25
brew
Homebrew
安装
​赞同 3700​
​962 条评论
​分享
​喜欢
​收藏
​申请转载
​

赞同 3700

​
分享
文章被以下专栏收录
MAC专区
MAC专区
test好转
test好转
好的东西要分享
推荐阅读
MacBook使用笔记：安装Homebrew（M1）
MacBook使用笔记：安装Homebrew（M1）
程序员
brew install 和 brew cask install 的区别
brew install 和 brew cask install 的区别
算法集市
发表于算法集市
9 条进阶命令，把 HomeBrew 打造成管理第三方应用的 App Store
9 条进阶命令，把 HomeBrew 打造成管理第三方应用的 App Store
少数派
发表于少数派
Homebrew安装、卸载、可能的报错及解决方案_Mac
上一篇安装node， brew install node，问题又来了，-bash: brew: command not found，突然想起来，前两天把homebrew卸载了，翻翻笔记，2018年11月28日???，好记性不如烂笔头这句话真的要掂…

笑胖仔

962 条评论
​切换为时间排序
写下你的评论...



发布
知乎用户WWuqiL
知乎用户WWuqiL2020-03-10
老哥，专门上号感谢，爱你

​25
​回复
​踩
​ 举报
pain
pain回复知乎用户WWuqiL2021-11-29
同
​赞
​回复
​踩
​ 举报
666
666回复知乎用户WWuqiL01-12
同
​赞
​回复
​踩
​ 举报
Williams
Williams2020-03-06
我用了网上的各种方法都不行，今天用你的就可以了，太感谢了！！！

​92
​回复
​踩
​ 举报
曹宇
曹宇回复Williams2020-05-05
同理来此

​5
​回复
​踩
​ 举报
知乎用户知乎用户回复Williams2020-05-17
me too

​赞
​回复
​踩
​ 举报
查看全部 11 条回复
Kurama
Kurama2020-03-12
感谢大佬，成功了


​4
​回复
​踩
​ 举报
知乎用户知乎用户2020-03-08
大佬你好，我通过第一个自动脚本安装成功了 请问以后使用这个brew下载软件或者更新brew 它也是都从中科大的源下载的吗？

​4
​回复
​踩
​ 举报
金牛肖马
金牛肖马 (作者) 回复知乎用户2020-03-08
以后更新是国内源，软件如果国内源有缓存是从国内下载。
​赞
​回复
​踩
​ 举报
知乎用户知乎用户回复金牛肖马 (作者)2020-03-09
谢谢大佬！

​赞
​回复
​踩
​ 举报
展开其他 1 条回复
春风飞扬
春风飞扬2021-04-14
能安装成功brew -v

Homebrew 3.1.1-22-g586d25a-dirty
Homebrew/homebrew-core (git revision 0e9e7cf04d; last commit 2021-04-14)
Homebrew/homebrew-cask (git revision d56a00b5d5; last commit 2021-04-14)

但是 brew install python、java、php都不行:

Download failed: https://ghcr.io/v2/xxx
​4
​回复
​踩
​ 举报
皮卡皮卡咻
皮卡皮卡咻回复春风飞扬2021-04-14
我也出现了这个问题，大佬后来有解决么？

​赞
​回复
​踩
​ 举报
知乎用户知乎用户回复春风飞扬2021-04-15
同样

​赞
​回复
​踩
​ 举报
展开其他 2 条回复
optimus
optimus2020-03-20
只有你的方法才行


​3
​回复
​踩
​ 举报
Wolfman
Wolfman2020-03-16
绝对的高手， 网上7788的搞了几天 终于看到这个了，必须点赞。亲测有效。

​3
​回复
​踩
​ 举报
阿常
阿常2020-03-07
通过文章顺利安装，感谢🙏

​3
​回复
​踩
​ 举报
知乎用户知乎用户2021-10-05
如果遇到 SSL certificate problem: certificate has expired 错误
具体内容如下：
Cloning into '/usr/local/Homebrew'...
fatal: unable to access 'https://mirrors.ustc.edu.cn/brew.git/': SSL certificate problem: certificate has expired
m此步骤失败 '尝试再次运行自动脚本选择其他下载源或者切换网络'
[问题分析]：
该部分原因可能因为在此之前 安装过Git客户端 默认Git客户端安装是开启SSL证书验证功能 需要在终端中关闭该验证
[解决办法] :
前面都不是重点，重点是问题描述里面的最后一句 certificate problem: certificate has expired，意思是证书过期了。其实就是SSL卡住了你，因此最快的解决方法就是关掉SSL验证。



终端输入下方代码 关闭SSL证书验证：
git config --global http.sslVerify false
​3
​回复
​踩
​ 举报
头很大很头大
头很大很头大回复知乎用户2021-10-05
厉害，谢谢🙏
​赞
​回复
​踩
​ 举报
大灰狼
大灰狼2021-04-30
登录账号只为给你点赞

​2
​回复
​踩
​ 举报
寒沐
寒沐2021-03-04
==> 克隆Homebrew基本文件

fatal: Unable to read current working directory: No such file or directory
fatal: Unable to read current working directory: No such file or directory
未发现Git代理（属于正常状态）
Cloning into '/usr/local/Homebrew'...
fatal: Unable to read current working directory: No such file or directory
m此步骤失败 '尝试再次运行自动脚本选择其他下载源或者切换网络'



大神 请教一下 这是什么问题呢

​2
​回复
​踩
​ 举报
金牛肖马
金牛肖马 (作者) 回复寒沐2021-03-05
你把整个运行过程发我邮箱

​赞
​回复
​踩
​ 举报
老于
老于回复寒沐2021-05-04
我也遇到了这个问题, 于是我把这个sh文件放在本地, 在执行到这个报错之前打印了一下语句里的三个变量, 然后本地起一个静态文件服务器, 再执行安装, 又不报错了...

​赞
​回复
​踩
​ 举报
查看全部 6 条回复
一心待明月
一心待明月2020-05-05
啊，我找到问题了，要把shell换成bash，谢谢大佬的分享
​1
​回复
​踩
​ 举报
金牛肖马
金牛肖马 (作者) 回复一心待明月2020-05-05
额 之前那步报的错呀[好奇] 我看看
​赞
​回复
​踩
​ 举报
一心待明月
一心待明月回复一心待明月2020-05-05
问题解决啦，是mac更新后默认zsh，要bash才可以安装
​赞
​回复
​踩
​ 举报
生死画知
生死画知2020-03-18
牛逼，之前费了一个小时劲没装上，你这个轻松就搞定了，厉害！！！

​1
​回复
​踩
​ 举报
知乎用户知乎用户2020-03-17
感谢，几分钟搞定...之前搭梯子折腾一晚上都没成

​1
​回复
​踩
​ 举报
张成从小就帅
张成从小就帅2020-03-16
感谢大佬，完美哈哈

​1
​回复
​踩
​ 举报
木然
木然2020-03-16
特地登陆来赞你 下官方那个老是失败 这个一下子就可以了

​1
​回复
​踩
​ 举报
msx
msx2020-03-12
我也是在网上找了好多办法，不行，大佬这个真是太好用了，谢谢

​1
​回复
​踩
​ 举报
咸鱼不想翻身
咸鱼不想翻身2021-06-22
此处如果显示Password表示需要再次输入开机密码，输入完后回车
Cloning into '/opt/homebrew/Library/Taps/homebrew/homebrew-core'...
remote: Enumerating objects: 977183, done.
error: RPC failed; curl 56 LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 54
fetch-pack: unexpected disconnect while reading sideband packet
fatal: early EOF
fatal: index-pack failed
m此步骤失败 '尝试再次运行自动脚本选择其他下载源或者切换网络'







到这就报错了，来回试了好几次，都不行
​1
​回复
​踩
​ 举报
233333
233333回复咸鱼不想翻身2021-07-07
校园网啥的公用网络不稳定性大
​赞
​回复
​踩
​ 举报
咸鱼不想翻身
咸鱼不想翻身2021-06-22
Cloning into '/opt/homebrew/Library/Taps/homebrew/homebrew-core'...
remote: Enumerating objects: 977183, done.
error: RPC failed; curl 56 LibreSSL SSL_read: SSL_ERROR_SYSCALL, errno 54
fetch-pack: unexpected disconnect while reading sideband packet
fatal: early EOF
fatal: index-pack failed



失败了怎么办，来回安装好几次了，都不行
​1
​回复
​踩
​ 举报
233333
233333回复咸鱼不想翻身2021-07-07
我也卡到这里了
​赞
​回复
​踩
​ 举报
深度学习患者
深度学习患者2021-04-15
install 404 error的朋友们，改一下环境变量，我昨晚摸索出来了https://zhuanlan.zhihu.com/p/364932701
​1
​回复
​踩
​ 举报
1234...36下一页

选择语言
