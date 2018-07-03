

# IDEA-IME-BUG
JAVA IDEA 中文输入法悬浮窗不跟随光标的玄学 BUG 解决方案：[52geek.top][1]

----------
![][2]

以上是知乎答案。

神级JAVA IDE 之 IDEA 玄学bug：中文输入法候选词悬浮窗不跟随光标问题已经彻底解决，为什么标题说是玄学，因为很多用户反馈就算环境一样软件一样，也会有不一样的结果，同样都是win10 配 JDK1.8.0.121+ IDEA 2018，有的人就是没问题，但是有人就有问题。

但是本人参考了知乎高票答案依然无解，自己折腾了一晚上终于按照如下方法搞定。

更新JDK 到1.80_172【很重要】

更新JDK 到1.80_172【很重要】

更新JDK 到1.80_172【很重要】


，然后你可能需要将IDEA 安装路径下的jre 32 和 jre 64 改名，也就是让idea 调用系统安装的JDK，注意提前设置好JDK环境变量即可。
🤗🤔🤓
搞定以上步骤，重启IDEA 完美解决。

![][3]

![][4]

![这张图怎么就显示不全呢？][5]

[52geek.top][6]：
JAVA IDEA 输入法悬浮窗不跟随光标的bug已经彻底解决


  [1]: https://52geek.top/88/
  [2]: https://52geek.top/wp-content/uploads/2018/07/chrome20180702_102553.png
  [3]: https://52geek.top/wp-content/uploads/2018/07/idea64_2018-07-02_00-03-53.png
  [4]: https://52geek.top/wp-content/uploads/2018/07/cmd_2018-07-02_00-10-06.png
  [5]: http://p7fcrq2e4.bkt.clouddn.com/201818021119-idea64_2018-07-02_00-09-35.png
  [6]: https://52geek.top/88/
