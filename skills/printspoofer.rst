PrintSpoofer
===========================

PrintSpoofer


渗透测试之地基免杀篇：PrintSpoofer底层分析免杀
-----------------

`渗透测试之地基免杀篇：PrintSpoofer底层分析免杀`_

PrintSpoofer是一款在Windows 10 和 Windows Service 2016/2019 环境下将低权限提升为SYSTEM权限的工具，在红队工具仓库工具之一，360会自动查杀该工具。

目前免杀主流的方法是利用脚本、加密工具进行套一层壳，利用.ps1脚本和套壳引用工具打开PrintSpoofer从而起到一个躲避杀软静态查杀达到免杀的效果，都是依赖于工具和脚本，如果工具和脚本失效了将无法进行免杀了...该工具的是非常主流的，往后会有更多的杀软会对其进行拦截查杀，今天就带大家利用Visual Studio 2019查看PrintSpoofer底层信息，如何进行免杀的过程。

.. _渗透测试之地基免杀篇：PrintSpoofer底层分析免杀: https://www.freebuf.com/articles/web/261444.html

