#### 基本情况

先说一下个人基本情况，山东渣一本大三学生，计算机科学与技术专业。主要学的Android开发，所以投的岗位都是Android开发工程师。过完年开始准备找实习，投了知乎，内推了阿里蘑菇街腾讯百度网易。腾讯百度都没有收到面试，知乎Skype面试，蘑菇街阿里电话面试，网易现场面。知乎二面被拒，蘑菇街阿里一面被拒，网易三面，然后备胎了，前几天被通知过了，收到了offer。自己整理了一下被问到的问题，现在分享给大家，另外自己整理的一下资料也会发给大家，希望能帮助到各位求职的小伙伴。

吐槽一句，牛客发帖不支持markdown，只能用本地写好了提交html了......

#### 知乎

知乎面试前hr会事先跟你电话确定面试时间，然后把你的Skype账号给hr，到时候面试官会加你好友，然后开始面试。知乎的招聘信息在[这里](http://www.zhihu.com/jobs)

一面：

- 自我介绍
- 介绍一下自己做过什么项目 ps：这里会根据项目问一些问题
- 跨线程通信  主要涉及`Looper` `Message` `Handler` 以及 `MessageQueue`
- 说一下自定义View需要注意哪些细节 主要说了一下View绘制的三大过程 `onDraw()`不要做耗时操作 不要创建新对象 以及 怎么处理View的触摸事件
- View的事件冲突的解决办法 ps：重写dispatchEvent()或者touch()方法
- 手写代码：给你一个无限大的数(用字符串表示)，计算这个数加一以后的结果 手写代码在[这个网站](http://collabedit.com/)进行 ps：面试官发给你一个链接 你写代码面试官会同步看到

二面

- 手写代码 两个有序链表合并成一个有序链表
- Object中有哪些公有方法 ps：`clone();toString();wait();notify();getClass();finalize();equals();hashCode();`
- 讲一下listView的优化方法
- 讲一下RecycleView与listview的区别
- view的绘制过程

#### 阿里

- 问了一下大体情况 比如什么时候可以实习啊 考不考研啊
- 都会什么算法 讲一下
- 做过什么项目没有 讲一下项目优化的地方
- Activity的启动模式
- 跨线程通信
- 夸进程通信 主要是Android的AIDL
- 如何解析json数据和xml

#### 蘑菇街

- 说说做了什么项目
- 自定义view的几个步骤 怎么刷新view ps：`onLayout(); onMeasrue();onDraw();`
- RecycleView的优化
- 几种context的区别
- 看过什么源码没有
- 讲一下binder类
- Runnable运行在哪个线程里面 ps：开启一个子线程的唯一方法就是`new Thread().start();`
- HashMap和HashTable的区别
- raw和assets文件夹的区别
- activity关闭后尚未运行完毕的thread会怎么样 ps：会变成空进程线程，优先级最低 很容易被终止回收
- mainfest文件的合并规则

#### 网易

网易内推后笔试，过了笔试后去杭州面试 ps：报销来回车费 报销上限是600元
这个回来没记 可能不全

一面：

- 自我介绍
- 跨线程通信
- 讲了其中一个项目是怎么实现的 问`jsoup`怎么拼 = =
- 用过哪些开源库 讲一下他的架构是怎样的
- java的四种引用 虚引用的作用
- 图片三级缓存 内存缓存满了怎么办 ps：优先级队列 满了后根据优先级主动删除一部分图片 根据LRU算法确定优先级
- 讲一下JNI开发的过程 java怎么找到c函数 ps：JNINativeMethod保存函数对应关系 有兴趣的小伙伴可以查看我的这篇[博客](http://bornbeauty.github.io/2016/04/05/jni.html)
- 平时有什么爱好没有 = = ps：潜泳 可以潜好几天 然后自己浮上来

二面：

- activity的四中启动模式
- service的生命周期
- 讲一下自己的项目
- 项目中用JNI做什么 为什么要用他呢
- 什么是OAuth协议 做什么的
- 其他的记不清楚了

hr面：

- 什么时候可以来实习 实习多久
- 多个offer怎么选
- 你有团队开发经验 内部冲突怎么解决
- 你觉得杭州怎么样
- 为什么选择网易
- 用过网易什么产品 ps：吃过网易猪肉
- 其他忘记 好像聊了好久 得一个小时吧

#### 资料

下面是自己整理的资料：

[Android&Java](http://bornbeauty.github.io/assets/file/androidjava.pdf)

[计算机网络&操作系统&数据结构](http://bornbeauty.github.io/assets/file/network.pdf)

[Java虚拟机](http://bornbeauty.github.io/assets/file/javaxuji.pdf)

[Git命令](http://bornbeauty.github.io/assets/file/git.pdf)

#### 广告

[个人网站](http://bornbeauty.github.io)

[github](http://www.github.com/bornbeauty)

[微博](http://www.weibo.com/zhongjinbao1994)

[知乎](http://www.zhihu.com/people/zhong-xiao-bao-2)