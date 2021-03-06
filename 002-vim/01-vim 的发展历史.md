vi 的创始人叫比尔乔伊，是 sun 公司的合伙人，vi 的前身可以说是 ed，关于 vi 的发展历史，我总结了这张节点图，详细请看本节视频了解。

![](http://processon.com/chart_image/5fd87cc663768906e6e05a3c.png)


文字版本如下:

1964 年，在加州伯克利分校，由于早期 Unix 分时操作系统的编写过程中，需要编写内核，缺少命令行文本编辑工具，当时的大神发明了 QED 小程序，意思就是 quick editor 快速编辑器。当时在贝尔实验室，肯汤普森其中一项工作就是把 QED 移植到大型的分时操作系统之上，后面肯汤普森发明了 Unix，QED 也被带进了 Unix，成为了 ed 组件，此外这个 ed 还衍生出了一系列的 Unix 命令，比如著名的 grep 和 sed，事实上 ed 已经成为当时 Unix 操作系统的标配。

1975 年肯汤普森回到伯克利分校，准备把 Unix 移植到伯克利分校自己的电脑上(也就是后来的伯克利软件套装 BSD)，当时 Unix 很流行，所以用 ed 的人也很多，但是大多数人来说这玩意儿真的是太难用了。

有一个大学的讲师开始着手修改 ed，并且改名为 em(the editor for mortals 给凡人用的编辑器)，在学校读研的学生比尔乔伊受到很大的启发，要来了 em 的源代码，在其基础上不断的修改，改名为 en，一直修改，一直改名，最后名称变为了 ex，1977 年他在 ex 的基础上，增加全屏幕显示的功能，并命名为 ex 的可视化模式，别名 vi。下图就是他。

![](http://develop-developer.oss-cn-hangzhou.aliyuncs.com/images/32ftNkuarpmnEDGEn-i3AByL8QO7vVl_fj7vwGg-mY.webp?x-oss-process=style/txt-water)

当时他使用的电脑的布局是这样的:

![](http://develop-developer.oss-cn-hangzhou.aliyuncs.com/images/ic9FfrmSkg2YK7Nee-XaOKkYJeEYNB31ckcmE5UDK2.png?x-oss-process=style/txt-water)

主要看这个键盘的方向键(当时其他的键盘方向大都也是横起的)，不是我们今天打游戏的WASD，这个键盘的 ESC 和 HOME 键也比较特殊，难怪 Unix 的 ~ 表示主目录。此后 vi 一直改善，因为当时其实还没有鼠标，所以 vi 一直都是一个基于模式(需要在编辑模式和命令模式之间来回切换)的软件，拥有各式各样的命令。

1982 年，三个斯坦福的学生创办了 sun 公司，比尔乔伊也被挖了过去，但是伯克利分校的 BSD 的 vi 因为 AT&T 挑起的官司，控告 BSD 侵犯了知识产权， 因为 vi 是基于 BSD 开发的，也被禁止在伯克利大学继续开发迭代，但是很多 vi 的粉丝并不愿意使用 emacs (理查德斯托曼搞的自由免费开源的 GNU 软件)，在 1990 年有人就发布了 vi 的克隆版 nvi (new vi)，被纳入了 BSD，一直沿用至今。

2000 年，有人基于比尔乔伊的源代码，冒死把 vi 发布到托瓦尔兹林纳斯的 linux 和 FreeBSD 操作上，但随着相关授权的解除，vi 最终成了合法的版本。由于 linux 的普及，以及 Mac OSX 和 BSD 变种流行， vi 当仁不让成为各大系统的标配，成为了编辑器的王者。

从 vi 发布以后，很多人模仿克隆，Vim 脱颖而出，它把工作重点方放在了兼容性处理上，1993 年正式使用 Vim (vi improvede) 为名称发布，距今已经是 30 年了，在最流行的开发环境中，2019 年的 StackOverflow 的调查中 Vim 排名第 4 位，大约 25% 的 Web 开发人员在使用它。

今天，Vim 和 Emacs 这 2 大阵营的人经常在掐架(就像是争论到底学 Java 好还是 PHP 好)，其实理解是高手在切磋武艺更合适，它们都是了不起的软件，并且见证了整个计算机和操作系统的发展历史。

vi 为纯键盘操作而优化，所以熟悉 vi 的人很喜欢那种键盘不离手的感觉(不需要去操作鼠标)，使用 vi 有一定的学习成本，但是熟悉后就可以起飞。他们爱它，恨它，最终离不开它。

今天有很多优秀的图形化文本编辑软件，我们并不一定非要用 vi 来做主流的 IDE(对，Vim 可以配置成非常牛掰的 IDE)，但是熟悉 vi 会使你在服务器文件上更加自由的穿梭，游刃有余。



// 视频
