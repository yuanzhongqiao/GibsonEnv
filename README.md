<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于具有现实世界感知的具体主动代理的 GIBSON ENVIRONMENT</font></font></h1><a id="user-content-gibson-environment-for-embodied-active-agents-with-real-world-perception" class="anchor" aria-label="永久链接：具有现实世界感知的具体主动代理的吉布森环境" href="#gibson-environment-for-embodied-active-agents-with-real-world-perception"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">你不应该整天玩电子游戏，你的人工智能也不应该！</font><font style="vertical-align: inherit;">我们构建了一个虚拟环境模拟器 Gibson，它为学习感知提供了真实世界的体验。</font></font></p>
<p dir="auto"><animated-image data-catalyst="" style="width: 600px;"><a target="_blank" rel="noopener noreferrer" href="https://github.com/StanfordVL/GibsonEnv/blob/master/misc/ui.gif" data-target="animated-image.originalLink"><img src="https://github.com/StanfordVL/GibsonEnv/raw/master/misc/ui.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
     
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">摘要</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">： 感知和活跃（即具有一定程度的运动自由度）密切相关。</font><font style="vertical-align: inherit;">在物理世界中学习主动感知和感觉运动控制非常麻烦，因为现有算法太慢，无法有效地实时学习，而且机器人脆弱且成本高昂。</font><font style="vertical-align: inherit;">这使得模拟学习取得了丰硕的成果，从而提出了如何转移到现实世界的问题。</font><font style="vertical-align: inherit;">我们开发的 Gibson 环境具有以下主要特征：</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一、</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来自现实世界，通过虚拟现实空间反映其语义复杂性，</font></font><br>
<strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二．</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有转移到现实世界的内置机制（护目镜功能），以及</font></font><br>
<strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">III。</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代理的体现，并通过集成物理引擎（</font></font><a href="http://bulletphysics.org/wordpress/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bulletphysicals</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）使其受到空间和物理的约束。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命名：吉布森环境以</font></font></strong><font style="vertical-align: inherit;"></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">James J. Gibson</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命名</font><font style="vertical-align: inherit;">，他是《视觉感知的生态方法》一书的作者，1979 年。“我们必须感知才能移动，但我们也必须移动才能感知” – JJ Gibson</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请访问</font></font><a href="http://gibson.vision/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">( </font></font><a href="http://gibsonenv.stanford.edu/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">http://gibsonenv.stanford.edu/</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ) 了解更多技术细节。</font><font style="vertical-align: inherit;">该存储库旨在用于分发环境和安装/运行说明。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸</font></font></h4><a id="user-content-paper" class="anchor" aria-label="永久链接：纸" href="#paper"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><a href="http://gibson.vision/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">“Gibson Env：体现代理的真实世界感知”</font></font></a></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> CVPR 2018 [Spotlight Oral]</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><a href="https://youtu.be/KdxuZjemyjc" title="点击观看总结 Gibson 环境的视频！" rel="nofollow"><img src="/StanfordVL/GibsonEnv/raw/master/misc/vid_thumbnail_600.png" alt="吉布森摘要视频" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布</font></font></h1><a id="user-content-release" class="anchor" aria-label="永久链接：发布" href="#release"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 0.3.1 版本。</font><font style="vertical-align: inherit;">我们鼓励并赞赏错误报告、改进建议以及社区发展。</font></font></strong> <a href="https://github.com/StanfordVL/GibsonEnv/blob/master/misc/CHANGELOG.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更改日志文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据库</font></font></h1><a id="user-content-database" class="anchor" aria-label="永久链接：数据库" href="#database"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完整的数据库包括 572 个空间和 1440 个楼层，可以</font></font><a href="/StanfordVL/GibsonEnv/blob/master/gibson/data/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载。</font></font><a href="http://gibsonenv.stanford.edu/database/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以看到吉布森所有空间的多样化可视化</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">为了使核心资产下载包对用户来说更轻松，我们包含了一小部分空间 (39)。</font><font style="vertical-align: inherit;">用户可以下载其余空间并将其添加到资产文件夹中。</font><font style="vertical-align: inherit;">如果您希望将 Gibson 的模拟器与这些数据集一起使用，</font><font style="vertical-align: inherit;">我们还将</font></font><a href="http://3dsemantics.stanford.edu/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯坦福 2D3DS</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://niessner.github.io/Matterport/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Matterport 3D集成为单独的数据集（</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/StanfordVL/GibsonEnv/blob/master/gibson/data/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问）。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h1><a id="user-content-table-of-contents" class="anchor" aria-label="永久链接：目录" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#installation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a>
<ul dir="auto">
<li><a href="#a-quick-installation-docker"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速安装（docker）</font></font></a></li>
<li><a href="#b-building-from-source"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源头构建</font></font></a></li>
<li><a href="#uninstalling"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卸载</font></font></a></li>
</ul>
</li>
<li><a href="#quick-start"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></a>
<ul dir="auto">
<li><a href="#gibson-framerate"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">吉布森第一人称射击游戏</font></font></a></li>
<li><a href="#web-user-interface"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网页用户界面</font></font></a></li>
<li><a href="#rendering-semantics"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">渲染语义</font></font></a></li>
<li><a href="#robotic-agents"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人代理</font></font></a></li>
<li><a href="#ros-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS配置</font></font></a></li>
</ul>
</li>
<li><a href="#coding-your-rl-agent"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编写 RL 代理的代码</font></font></a></li>
<li><a href="#environment-configuration"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境配置</font></font></a></li>
<li><a href="#goggles-transferring-the-agent-to-real-world"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">护目镜：将代理转移到现实世界</font></font></a></li>
<li><a href="#citation"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></a></li>
</ul>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h1><a id="user-content-installation" class="anchor" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装方法</font></font></h4><a id="user-content-installation-method" class="anchor" aria-label="永久链接：安装方法" href="#installation-method"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 gibson 有两种方法，A. 使用我们的 docker 镜像（推荐）和 B. 从源代码构建。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">系统要求</font></font></h4><a id="user-content-system-requirements" class="anchor" aria-label="永久链接：系统要求" href="#system-requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最低系统要求如下：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于 docker 安装（A）：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图16.04</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nvidia GPU，显存 &gt; 6.0GB</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nvidia 驱动程序 &gt;= 384</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CUDA &gt;= 9.0，CuDNN &gt;= v7</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于从源头构建（B）：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">乌班图 &gt;= 14.04</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nvidia GPU，显存 &gt; 6.0GB</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nvidia 驱动程序 &gt;= 375</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CUDA &gt;= 8.0，CuDNN &gt;= v5</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载数据</font></font></h4><a id="user-content-download-data" class="anchor" aria-label="永久链接：下载数据" href="#download-data"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，我们的环境核心资产数据可以</font></font><a href="https://storage.googleapis.com/gibson_scenes/assets_core_v2.tar.gz" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取。</font><font style="vertical-align: inherit;">您可以按照下面的安装指南正确下载并设置它们。</font></font><code>gibson/assets</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹存储运行gibson环境所需的数据（代理模型、环境等）。</font><font style="vertical-align: inherit;">用户可以添加更多环境文件以</font></font><code>gibson/assets/dataset</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在更多环境中运行gibson。</font><font style="vertical-align: inherit;">访问</font></font><a href="/StanfordVL/GibsonEnv/blob/master/gibson/data/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据库自述文件</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下载更多空间。</font><font style="vertical-align: inherit;">使用Gibson的数据库之前</font><font style="vertical-align: inherit;">请签署</font></font><a href="/StanfordVL/GibsonEnv/blob/master/gibson/data/README.md#download"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可协议。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">A.快速安装（docker）</font></font></h2><a id="user-content-a-quick-installation-docker" class="anchor" aria-label="永久链接：A.快速安装（docker）" href="#a-quick-installation-docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们使用docker来分发我们的软件，您需要先安装</font></font><a href="https://docs.docker.com/engine/installation/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">docker</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/nvidia/nvidia-docker/wiki/Installation-(version-2.0)"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nvidia-docker2.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行</font></font><code>docker run --runtime=nvidia --rm nvidia/cuda nvidia-smi</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以验证您的安装。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以 1. 从我们的 docker 映像中提取（推荐）或 2. 构建您自己的 docker 映像。</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从我们的 docker 镜像中提取（推荐）</font></font></li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> download the dataset from https://storage.googleapis.com/gibson_scenes/dataset.tar.gz</span>
docker pull xf1280/gibson:0.3.1
xhost +local:root
docker run --runtime=nvidia -ti --rm -e DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v <span class="pl-k">&lt;</span>host path to dataset folder<span class="pl-k">&gt;</span>:/root/mount/gibson/gibson/assets/dataset xf1280/gibson:0.3.1</pre><div class="zeroclipboard-container">
    
  </div></div>
<ol start="2" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建您自己的 docker 镜像</font></font></li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/StanfordVL/GibsonEnv.git
<span class="pl-c1">cd</span> GibsonEnv
./download.sh <span class="pl-c"><span class="pl-c">#</span> this script downloads assets data file and decompress it into gibson/assets folder</span>
docker build <span class="pl-c1">.</span> -t gibson <span class="pl-c"><span class="pl-c">#</span>## finish building inside docker, note by default, dataset will not be included in the docker images</span>
xhost +local:root <span class="pl-c"><span class="pl-c">#</span># enable display from docker</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果安装成功，您应该能够运行</font></font><code>docker run --runtime=nvidia -ti --rm -e DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v &lt;host path to dataset folder&gt;:/root/mount/gibson/gibson/assets/dataset gibson</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来创建容器。</font><font style="vertical-align: inherit;">请注意，我们不会在 docker 镜像中包含数据集文件以保持镜像精简，因此您需要在启动容器时将其安装到容器中。</font></font></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在无头服务器上部署的注意事项</font></font></h4><a id="user-content-notes-on-deployment-on-a-headless-server" class="anchor" aria-label="永久链接：有关在无头服务器上部署的注意事项" href="#notes-on-deployment-on-a-headless-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gibson Env 支持在无头服务器上部署以及使用</font></font><code>x11vnc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">. </font><font style="vertical-align: inherit;">您可以使用上面的 docker 文件构建自己的 docker 镜像</font></font><code>Dockerfile</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">在无头服务器上运行 gibson 的说明（需要运行 X 服务器）：</font></font></p>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照入门指南安装 nvidia-docker2 依赖项。</font><font style="vertical-align: inherit;">安装</font></font><code>x11vnc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与</font></font><code>sudo apt-get install x11vnc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">让 xserver 在您的主机上运行，&ZeroWidthSpace;&ZeroWidthSpace;并</font></font><code>x11vnc</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 DISPLAY :0 上运行。</font></font></li>
<li><code>docker run --runtime=nvidia -ti --rm -e DISPLAY -v /tmp/.X11-unix/X0:/tmp/.X11-unix/X0 -v &lt;host path to dataset folder&gt;:/root/mount/gibson/gibson/assets/dataset &lt;gibson image name&gt;</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用</font></font><code>python &lt;gibson example or training&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内部 docker 运行 gibson。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">访问您的</font></font><code>host:5900</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您应该能够看到 GUI。</font></font></li>
</ol>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您没有运行 X 服务器，您仍然可以运行 gibson，请参阅</font></font><a href="https://github.com/StanfordVL/GibsonEnv/wiki/Running-GibsonEnv-on-headless-server"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本指南</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多详细信息。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B. 从源头构建</font></font></h2><a id="user-content-b-building-from-source" class="anchor" aria-label="永久链接：B. 从源代码构建" href="#b-building-from-source"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果你不想使用我们的docker镜像，你也可以在本地安装gibson。</font><font style="vertical-align: inherit;">这将需要安装一些依赖项。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，确保您安装了 Nvidia 驱动程序和 CUDA。</font><font style="vertical-align: inherit;">如果从源代码安装，则不需要 CUDA 9，因为它适用于 nvidia-docker 2.0。</font><font style="vertical-align: inherit;">然后，让我们安装一些依赖项：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>apt-get update 
apt-get install libglew-dev libglm-dev libassimp-dev xorg-dev libglu1-mesa-dev libboost-dev \
		mesa-common-dev freeglut3-dev libopenmpi-dev cmake golang libjpeg-turbo8-dev wmctrl \
		xdotool libzmq3-dev zlib1g-dev</pre><div class="zeroclipboard-container">
  
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装所需的深度学习库：推荐使用python3.5。</font><font style="vertical-align: inherit;">可以先创建一个python3.5环境。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>conda create -n py35 python=3.5 anaconda 
<span class="pl-c1">source</span> activate py35 <span class="pl-c"><span class="pl-c">#</span> the rest of the steps needs to be performed in the conda environment</span>
conda install -c conda-forge opencv
pip install http://download.pytorch.org/whl/cu90/torch-0.3.1-cp35-cp35m-linux_x86_64.whl 
pip install torchvision==0.2.0
pip install tensorflow==1.3</pre><div class="zeroclipboard-container">
     
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">克隆存储库、下载数据并构建</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/StanfordVL/GibsonEnv.git
<span class="pl-c1">cd</span> GibsonEnv
./download.sh <span class="pl-c"><span class="pl-c">#</span> this script downloads assets data file and decompress it into gibson/assets folder</span>
./build.sh build_local <span class="pl-c"><span class="pl-c">#</span>## build C++ and CUDA files</span>
pip install -e <span class="pl-c1">.</span> <span class="pl-c"><span class="pl-c">#</span>## Install python libraries</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要运行训练演示，请安装 OpenAI 基线。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone https://github.com/fxia22/baselines.git
pip install -e baselines</pre><div class="zeroclipboard-container">
    
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卸载</font></font></h2><a id="user-content-uninstalling" class="anchor" aria-label="永久链接：卸载" href="#uninstalling"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">卸载 gibson 很简单。</font><font style="vertical-align: inherit;">如果你使用docker安装，只需运行</font></font><code>docker images -a | grep "gibson" | awk '{print $3}' | xargs docker rmi</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">清理镜像即可。</font><font style="vertical-align: inherit;">如果您从源安装，请使用卸载</font></font><code>pip uninstall gibson</code></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h1><a id="user-content-quick-start" class="anchor" aria-label="永久链接：快速入门" href="#quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>xhost +local:root</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先在您的主机上</font><font style="vertical-align: inherit;">运行以启用显示。</font><font style="vertical-align: inherit;">您可能需要</font></font><code>export DISPLAY=:0</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">先跑步。</font><font style="vertical-align: inherit;">使用 进入 docker 容器后</font></font><code>docker run --runtime=nvidia -ti --rm -e DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix -v &lt;host path to dataset folder&gt;:/root/mount/gibson/gibson/assets/dataset gibson</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，您将获得一个交互式 shell。</font><font style="vertical-align: inherit;">现在您可以运行一些演示。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您是从源代码安装的，则可以使用以下命令直接运行它们，而无需使用 docker。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python examples/demo/play_husky_nonviz.py <span class="pl-c"><span class="pl-c">#</span>## Use ASWD keys on your keyboard to control a car to navigate around Gates building</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python examples/demo/play_husky_nonviz.py ### Use ASWD keys on your keyboard to control a car to navigate around Gates building" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/StanfordVL/GibsonEnv/blob/master/misc/husky_nonviz.png"><img src="https://github.com/StanfordVL/GibsonEnv/raw/master/misc/husky_nonviz.png" width="600" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您将能够使用键盘上的 ASWD 键来控制汽车在盖茨大楼周围导航。</font><font style="vertical-align: inherit;">此特定演示中不会显示相机输出。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python examples/demo/play_husky_camera.py <span class="pl-c"><span class="pl-c">#</span>## Use ASWD keys on your keyboard to control a car to navigate around Gates building, while RGB and depth camera outputs are also shown.</span></pre><div class="zeroclipboard-container">
  
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/StanfordVL/GibsonEnv/blob/master/misc/husky_camera.png"><img src="/StanfordVL/GibsonEnv/raw/master/misc/husky_camera.png" width="600" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您将能够使用键盘上的 ASWD 键来控制汽车在盖茨大楼周围导航。</font><font style="vertical-align: inherit;">您还可以看到 RGB 和深度相机输出。</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python examples/train/train_husky_navigate_ppo2.py <span class="pl-c"><span class="pl-c">#</span>## Use PPO2 to train a car to navigate down the hallway in Gates building, using visual input from the camera.</span></pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/StanfordVL/GibsonEnv/blob/master/misc/husky_train.png"><img src="/StanfordVL/GibsonEnv/raw/master/misc/husky_train.png" width="800" style="max-width: 100%;"></a></p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
通过运行此命令，您将开始训练哈士奇机器人在盖茨大楼中导航并使用 RGBD 输入沿着走廊行走。</font><font style="vertical-align: inherit;">每集结束后，您将在终端中看到一些 RL 相关的统计数据。
</font></font><div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>python examples/train/train_ant_navigate_ppo1.py <span class="pl-c"><span class="pl-c">#</span>## Use PPO1 to train an ant to navigate down the hallway in Gates building, using visual input from the camera.</span></pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/StanfordVL/GibsonEnv/blob/master/misc/ant_train.png"><img src="/StanfordVL/GibsonEnv/raw/master/misc/ant_train.png" width="800" style="max-width: 100%;"></a></p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
通过运行此命令，您将开始训练蚂蚁在盖茨大楼中导航并使用 RGBD 输入沿着走廊行走。</font><font style="vertical-align: inherit;">每集结束后，您将在终端中看到一些 RL 相关的统计数据。
</font></font><div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">吉布森帧率</font></font></h2><a id="user-content-gibson-framerate" class="anchor" aria-label="永久链接：吉布森帧率" href="#gibson-framerate"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下是 Gibson Environment 在不同平台上的帧率基准。</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/StanfordVL/GibsonEnv/tree/fps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">fps 分支</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取重现结果的代码。</font></font></p>
<table>
  <tbody><tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台</font></font></th>
    <td colspan="3"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Intel E5-2697 v4 + NVIDIA Tesla V100 上测试</font></font></td>
  </tr>
  <tr>
    <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分辨率 [nxn]</font></font></th>
    <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">128</font></font></th>
    <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">256</font></font></th>
    <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第512章</font></font></th>
 </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RGBD，预网络</font></font><code>f</code></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">109.1</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">58.5</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">26.5</font></font></td>
  </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RGBD、后网络</font></font><code>f</code></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">77.7</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">30.6</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">14.5</font></font></td>
  </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">RGBD，后小网络</font></font><code>f</code></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">87.4</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">40.5</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">21.2</font></font></td>
  </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅深度</font></font></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">253.0</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">197.9</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">124.7</font></font></td>
  </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅表面法线</font></font></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">207.7</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">129.7</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">57.2</font></font></td>
  </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅语义</font></font></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">190.0</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">144.2</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">55.6</font></font></td>
  </tr>
  <tr>
    <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">非视觉感官</font></font></th>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">396.1</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">396.1</font></font></td>
    <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">396.1</font></font></td>
  </tr>
</tbody></table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还在</font></font><code>Intel I7 7700 + NVIDIA GeForce GTX 1070Ti</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>Tested on Intel I7 6580k + NVIDIA GTX 1080Ti</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台上进行了测试。</font><font style="vertical-align: inherit;">每个任务的 FPS 差异在 10% 以内。</font></font></p>
<table>
    <tbody><tr>
        <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">平台</font></font></th>
        <td colspan="6"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Intel E5-2697 v4 + NVIDIA Tesla V100 上测试多进程 FPS</font></font></td>
    </tr>
    <tr>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置</font></font></th>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">512x512 剧集同步</font></font></th>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">512x512 帧同步</font></font></th>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">256x256 剧集同步</font></font></th>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">256x256 帧同步</font></font></th>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">128x128 剧集同步</font></font></th>
      <th scope="col"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">128x128 帧同步</font></font></th>
    </tr>
    <tr>
      <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1 进程</font></font></th>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12.8</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12.02</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">32.98</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">32.98</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">52</font></font></td>
    </tr>
    <tr>
      <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2个过程</font></font></th>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">23.4</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">20.9</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">60.89</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">53.63</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">86.1</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">101.8</font></font></td>
    </tr>
    <tr>
      <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4道工序</font></font></th>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">42.4</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">31.97</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">105.26</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">76.23</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">97.6</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">145.9</font></font></td>
    </tr>
    <tr>
      <th scope="row"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8道工序</font></font></th>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">72.5</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">48.1</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">138.5</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">97.72</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">113</font></font></td>
      <td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">151</font></font></td>
    </tr>
</tbody></table>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/StanfordVL/GibsonEnv/blob/master/misc/mpi_fps.png"><img src="https://github.com/StanfordVL/GibsonEnv/raw/master/misc/mpi_fps.png" width="600" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网页用户界面</font></font></h2><a id="user-content-web-user-interface" class="anchor" aria-label="永久链接：网络用户界面" href="#web-user-interface"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行 Gibson 时，您可以使用 启动 Web 用户界面</font></font><code>python gibson/utils/web_ui.py python gibson/utils/web_ui.py 5552</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">当您无法物理访问运行 gibson 的计算机或在无头云环境中运行时，这非常有用。</font><font style="vertical-align: inherit;">您需要更改</font></font><code>mode</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置文件才能</font></font><code>web_ui</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 Web 用户界面。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/StanfordVL/GibsonEnv/blob/master/misc/web_ui.png"><img src="/StanfordVL/GibsonEnv/raw/master/misc/web_ui.png" width="600" style="max-width: 100%;"></a></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">渲染语义</font></font></h2><a id="user-content-rendering-semantics" class="anchor" aria-label="永久链接：渲染语义" href="#rendering-semantics"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/StanfordVL/GibsonEnv/blob/master/misc/instance_colorcoding_semantics.png"><img src="/StanfordVL/GibsonEnv/raw/master/misc/instance_colorcoding_semantics.png" width="600" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">当模型被语义注释时，Gibson 可以提供逐像素的逐帧语义掩码。</font><font style="vertical-align: inherit;">截至目前，我们已</font><font style="vertical-align: inherit;">为此目的整合了</font></font><a href="http://buildingparser.stanford.edu/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯坦福 2D-3D-语义数据集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://niessner.github.io/Matterport/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Matterport 3D的模型。</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/StanfordVL/GibsonEnv/blob/master/gibson/data/README.md#download-gibson-database-of-spaces"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gibson 中访问它们</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">我们建议您参考原始数据集的参考，以获取其语义类和注释的列表。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关 Gibson 中渲染语义的详细说明，请参阅</font></font><a href="/StanfordVL/GibsonEnv/blob/master/gibson/utils/semantics.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">语义说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">作为安装附带的入门数据集中的一个示例，</font></font><code>space7</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">包括斯坦福 2D-3D-Semantics 风格注释。</font></font></p>

<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人代理</font></font></h2><a id="user-content-robotic-agents" class="anchor" aria-label="永久链接：机器人代理" href="#robotic-agents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gibson 提供了一组基本代理。</font></font><a href="http://gibsonenv.stanford.edu/agents/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看这些代理的视频及其相应的感知观察</font><font style="vertical-align: inherit;">。
</font></font><animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer" href="/StanfordVL/GibsonEnv/blob/master/misc/agents.gif" data-target="animated-image.originalLink"><img src="/StanfordVL/GibsonEnv/raw/master/misc/agents.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
     
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了（可选）抽象出低级控制和机器人动力学来执行高级任务，我们还为每个代理提供了一组实用且理想的控制器。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代理名称</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自由度</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">信息</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">控制器</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">穆乔科蚂蚁</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8</font></font></td>
<td align="center"><a href="https://blog.openai.com/roboschool/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放人工智能链接</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭矩</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">穆乔科人形生物</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">17 号</font></font></td>
<td align="center"><a href="https://blog.openai.com/roboschool/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开放人工智能链接</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭矩</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈士奇机器人</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4</font></font></td>
<td align="center"><a href="http://wiki.ros.org/Robots/Husky" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">活性氧</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><a href="https://www.clearpathrobotics.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制造商</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭矩、速度、位置</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">小牛机器人</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">8</font></font></td>
<td align="center"><a href="https://www.ghostrobotics.io/copy-of-robots" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，</font></font><a href="https://www.ghostrobotics.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制造商</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">正弦控制器</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">兔子杰克</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td align="center"><a href="http://cvgl.stanford.edu/projects/jackrabbot/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">斯坦福项目链接</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭矩、速度、位置</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">海龟机器人</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td align="center"><a href="http://wiki.ros.org/Robots/TurtleBot" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">活性氧</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">,</font></font><a href="https://www.turtlebot.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">制造商</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扭矩、速度、位置</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">四旋翼飞行器</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">6</font></font></td>
<td align="center"><a href="https://repository.upenn.edu/cgi/viewcontent.cgi?referer=https://www.google.com/&amp;httpsredir=1&amp;article=1705&amp;context=edissertations" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">纸</font></font></a></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">位置</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">起始代码</font></font></h3><a id="user-content-starter-code" class="anchor" aria-label="永久链接：起始代码" href="#starter-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>examples/demo</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多演示示例可以在文件夹</font><font style="vertical-align: inherit;">中找到</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解释</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><code>play_ant_camera.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 1234567890qwerty 键控制蚂蚁在盖茨大楼周围导航，同时还会显示 RGB 和深度相机输出。</font></font></td>
</tr>
<tr>
<td align="center"><code>play_ant_nonviz.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 1234567890qwerty 键来控制蚂蚁在盖茨大楼周围导航。</font></font></td>
</tr>
<tr>
<td align="center"><code>play_drone_camera.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 ASWDZX 键控制无人机在盖茨大楼周围导航，同时还会显示 RGB 和深度相机输出。</font></font></td>
</tr>
<tr>
<td align="center"><code>play_drone_nonviz.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 ASWDZX 键控制无人机在盖茨大楼周围导航</font></font></td>
</tr>
<tr>
<td align="center"><code>play_humanoid_camera.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 1234567890qwertui 键来控制人形机器人在盖茨大楼周围导航。</font><font style="vertical-align: inherit;">开个玩笑，用键盘控制人形太难了，只能眼睁睁看着它掉下来。</font><font style="vertical-align: inherit;">按 R 重置。</font><font style="vertical-align: inherit;">还显示了 RGB 和深度相机输出。</font></font></td>
</tr>
<tr>
<td align="center"><code>play_humanoid_nonviz.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">观看人形物体坠落。</font><font style="vertical-align: inherit;">按 R 重置。</font></font></td>
</tr>
<tr>
<td align="center"><code>play_husky_camera.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 ASWD 键控制汽车在盖茨大楼周围导航，同时还会显示 RGB 和深度摄像头输出。</font></font></td>
</tr>
<tr>
<td align="center"><code>play_husky_nonviz.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用键盘上的 ASWD 键控制汽车在盖茨大楼周围导航</font></font></td>
</tr>
</tbody>
</table>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多训练代码可以在文件夹中找到</font></font><code>examples/train</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解释</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><code>train_husky_navigate_ppo2.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PPO2 使用摄像头的 RGBD 输入来训练汽车沿着盖茨大楼的走廊行驶。</font></font></td>
</tr>
<tr>
<td align="center"><code>train_husky_navigate_ppo1.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">&nbsp; 使用 PPO1 使用摄像头的 RGBD 输入来训练汽车沿着盖茨大楼的走廊行驶。</font></font></td>
</tr>
<tr>
<td align="center"><code>train_ant_navigate_ppo1.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PPO1 训练蚂蚁通过摄像头的视觉输入沿着盖茨大楼的走廊导航。</font></font></td>
</tr>
<tr>
<td align="center"><code>train_ant_climb_ppo1.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PPO1 通过摄像头的视觉输入来训练蚂蚁爬下盖茨大楼的楼梯。</font></font></td>
</tr>
<tr>
<td align="center"><code>train_ant_gibson_flagrun_ppo1.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PPO1 训练蚂蚁追逐盖茨大楼中的目标（红色立方体）。</font><font style="vertical-align: inherit;">每当蚂蚁到达目标（或超时）时，目标就会改变位置。</font></font></td>
</tr>
<tr>
<td align="center"><code>train_husky_gibson_flagrun_ppo1.py</code></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 PPO1 训练汽车追逐盖茨大楼中的目标（红色立方体）。</font><font style="vertical-align: inherit;">每次汽车到达目标（或超时）时，目标都会改变位置。</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ROS配置</font></font></h2><a id="user-content-ros-configuration" class="anchor" aria-label="永久链接：ROS 配置" href="#ros-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="/StanfordVL/GibsonEnv/blob/master/examples/ros/gibson-ros"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了使用 ROS 配置 Gibson 的示例</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">我们以turtlebot为例，在Gibson中训练策略后，只需进行最少的更改即可部署到turtlebot上。</font><font style="vertical-align: inherit;">有关更多详细信息，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://github.com/StanfordVL/GibsonEnv/blob/master/examples/ros/gibson-ros"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自述文件。</font></font></a><font style="vertical-align: inherit;"></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编写 RL 代理的代码</font></font></h1><a id="user-content-coding-your-rl-agent" class="anchor" aria-label="永久链接：编写 RL 代理代码" href="#coding-your-rl-agent"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以按照我们的约定对您的 RL 代理进行编码。</font><font style="vertical-align: inherit;">我们的环境的接口非常简单（请参阅本节末尾的一些示例）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，您可以通过在文件夹中创建类的实例来创建环境</font></font><code>gibson/core/envs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">env</span> <span class="pl-c1">=</span> <span class="pl-v">AntNavigateEnv</span>(<span class="pl-s1">is_discrete</span><span class="pl-c1">=</span><span class="pl-c1">False</span>, <span class="pl-s1">config</span> <span class="pl-c1">=</span> <span class="pl-s1">config_file</span>)</pre><div class="zeroclipboard-container">
   
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后用 进行一步模拟</font></font><code>env.step</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">并重置</font></font><code>env.reset()</code></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">obs</span>, <span class="pl-s1">rew</span>, <span class="pl-s1">env_done</span>, <span class="pl-s1">info</span> <span class="pl-c1">=</span> <span class="pl-s1">env</span>.<span class="pl-en">step</span>(<span class="pl-s1">action</span>)</pre><div class="zeroclipboard-container">
    
  </div></div>
<p dir="auto"><code>obs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">给出机器人的观察结果。</font><font style="vertical-align: inherit;">它是一个字典，每个组件作为键值对。</font><font style="vertical-align: inherit;">它的键由用户在配置文件中指定。</font><font style="vertical-align: inherit;">例如</font></font><code>obs['nonviz_sensor']</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是本体感受传感器数据，</font></font><code>obs['rgb_filled']</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是RGB相机数据。</font></font></p>
<p dir="auto"><code>rew</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是定义的奖励。</font></font><code>env_done</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">标志着一集的结束，例如机器人死亡时。
</font></font><code>info</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">给出此步骤的一些附加信息；</font><font style="vertical-align: inherit;">有时我们用它来传递额外的非视觉传感器值。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在设计 RL 算法和环境的接口时，</font><font style="vertical-align: inherit;">我们主要遵循</font></font><a href="https://github.com/openai/gym"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAIgym惯例。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了帮助用户更快地开始使用该环境，我们在</font></font><a href="/StanfordVL/GibsonEnv/blob/master/examples/train"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Examples/train</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中提供了一些示例。</font><font style="vertical-align: inherit;">我们使用的强化学习算法来自</font></font><a href="https://github.com/openai/baselines"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">openAI 基线</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并进行了一些调整，以处理混合视觉和非视觉感官数据。</font><font style="vertical-align: inherit;">特别是，我们使用了</font></font><a href="https://github.com/openai/baselines/tree/master/baselines/ppo1"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PPO和</font></font></a><font style="vertical-align: inherit;"></font><a href="https://github.com/openai/baselines/tree/master/baselines/ppo2"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">PPO</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的速度优化版本</font><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境配置</font></font></h1><a id="user-content-environment-configuration" class="anchor" aria-label="永久链接：环境配置" href="#environment-configuration"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个环境都配置有一个</font></font><code>yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件。</font><font style="vertical-align: inherit;">文件示例</font></font><code>yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在文件夹中找到</font></font><code>examples/configs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">该文件的参数解释如下。</font><font style="vertical-align: inherit;">有关 Bullet 物理引擎的更多信息，您可以</font></font><a href="https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看文档。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">参数名称</font></font></th>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">示例值</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解释</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境名称</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AntClimb环境</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境名称，确保与环境的类名相同</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">型号_id</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">空间1-空间8</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">场景id，在测试版中，从space1-space8中选择</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标_orn</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[0, 0, 3.14]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欧拉角（弧度）导航目标方向，参考系为世界系。</font><font style="vertical-align: inherit;">对于非导航任务，该参数被忽略。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标位置</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[-7, 2.6, -1.5]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导航的目标位置（以米为单位），参考系为世界系。</font><font style="vertical-align: inherit;">对于非导航任务，该参数被忽略。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始_orn</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[0, 0, 3.14]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导航的初始方向（以弧度为单位），参考系为世界系</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始位置</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[-7, 2.6, 0.5]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导航的初始位置（以米为单位），参考系为世界系</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视场</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1.57</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相机的视野，以弧度为单位</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用填充剂</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">真假</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是否使用神经网络填充器。</font><font style="vertical-align: inherit;">建议将此参数保留为真。</font><font style="vertical-align: inherit;">请参阅</font></font><a href="http://gibson.vision/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">吉布森环境网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多信息。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显示用户界面</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">真假</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gibson 有两种显示视觉输出的方式，要么在多个窗口中，要么将它们聚合到一个 pygame 窗口中。</font><font style="vertical-align: inherit;">该参数决定是否显示pygame ui，如果在生产环境（训练），则需要将其关闭</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显示诊断</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">真假</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">显示叠加在 RGB 图像上的诊断信息（包括 fps、机器人位置和方向、累积奖励）</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户界面编号</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要显示多少个 ui 组件，这应该是 ui_components 的长度。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户界面组件</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[RGB_FILLED，深度]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 ui 组件，从 [RGB_FILLED、DEPTH、NORMAL、SEMANTICS、RGB_PREFILLED] 中选择</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">输出</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[nonviz_sensor、rgb_filled、深度]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将环境输出到机器人，从 [nonviz_sensor、rgb_filled、深度] 中选择。</font><font style="vertical-align: inherit;">这些值与 无关</font></font><code>ui_components</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，因为</font></font><code>ui_components</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它决定了显示内容并</font></font><code>output</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">决定了机器人接收的内容。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第512章</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从 [128, 256, 512] 分辨率中选择 RGB/深度图像</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">初始_orn</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[0, 0, 3.14]</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">导航的初始方向（以弧度为单位），参考系为世界系</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">速度：时间步长</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">0.01</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个物理模拟步骤的长度（以秒为单位）（如</font></font><a href="https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bullet</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中所定义）。</font><font style="vertical-align: inherit;">例如，如果 timestep=0.01 秒，frameskip=10，并且环境以 100fps 运行，则它将是 10 倍实时。</font><font style="vertical-align: inherit;">注意：将时间步设置为高于 0.1 可能会导致当前版本的 Bullet 模拟器不稳定，因为对象在一个时间步内的移动速度不应超过其自身半径。</font><font style="vertical-align: inherit;">您可以将时间步长保持在较低值，但增加跳帧以更快的速度进行模拟。</font><font style="vertical-align: inherit;">有关详细信息，请参阅</font><font style="vertical-align: inherit;">“离散碰撞检测”下的</font></font><a href="https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目符号指南。</font></font></a><font style="vertical-align: inherit;"></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">速度：跳帧</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">10</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">渲染帧时要跳过多少时间步。</font><font style="vertical-align: inherit;">请参阅上行的示例。</font><font style="vertical-align: inherit;">对于不需要高频控制的任务，可以将frameskip设置为更大的值以获得进一步的加速。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">模式</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图形用户界面/无头/web_ui</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gui 或 headless，如果在生产环境（训练），则需要将其转为 headless。</font><font style="vertical-align: inherit;">gui模式下，会有视觉输出；</font><font style="vertical-align: inherit;">在无头模式下，不会有任何视觉输出。</font><font style="vertical-align: inherit;">除此之外，如果将模式设置为 web_ui，它将像无头模式一样运行，但视觉效果将呈现到 Web UI 服务器。</font><font style="vertical-align: inherit;">（</font></font><a href="#web-user-interface"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多信息</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">冗长的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">真假</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在终端中显示诊断信息</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">fast_lq_render</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">真假</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果 yaml 文件中有 fast_lq_render，Gibson 将使用较小的填充网络，这将渲染速度更快，但生成质量稍低的相机输出。</font><font style="vertical-align: inherit;">此选项对于快速训练 RL 代理非常有用。</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">打造您的定制环境</font></font></h4><a id="user-content-making-your-customized-environment" class="anchor" aria-label="永久链接：打造您的定制环境" href="#making-your-customized-environment"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gibson 提供了一组方法供您定义自己的环境。</font><font style="vertical-align: inherit;">您可以按照里面现有的环境进行操作</font></font><code>gibson/core/envs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<table>
<thead>
<tr>
<th align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方法名称</font></font></th>
<th align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.render_observation（姿势）</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据姿势渲染新的观察结果，返回字典。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.get_observation()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以当前姿势进行观察。</font><font style="vertical-align: inherit;">需要在robot.render_observation(pose)之后调用。</font><font style="vertical-align: inherit;">这不会引起额外的计算。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.get_position()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取当前机器人位置。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.get_orientation()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取当前机器人方向。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.眼睛.get_position()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取当前机器人感知相机位置。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.眼睛.get_orientation()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取当前机器人感知相机方向。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.get_target_position()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取机器人目标位置。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.apply_action(动作)</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对机器人应用动作。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.reset_new_pose(pos, orn)</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将机器人重置为任意姿势。</font></font></td>
</tr>
<tr>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">机器人.dist_to_target()</font></font></td>
<td align="left"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取机器人到目标的当前距离。</font></font></td>
</tr>
</tbody>
</table>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">护目镜：将代理转移到现实世界</font></font></h1><a id="user-content-goggles-transferring-the-agent-to-real-world" class="anchor" aria-label="永久链接：Goggles：将代理转移到现实世界" href="#goggles-transferring-the-agent-to-real-world"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Gibson 包含一个名为 Goggles 的内置域适应机制，用于在 Gibson 中训练的代理将被部署到现实世界中时（即根据来自机载摄像头的图像进行操作）。</font><font style="vertical-align: inherit;">该机制本质上是一种学习的逆函数，它将来自真实相机的帧更改为通过吉布森渲染的帧，从而消除域间隙。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/6197ef9a1041f279b841b3164271cc4294044e845c5c6ee8acee1d95519ccb43/687474703a2f2f676962736f6e2e766973696f6e2f7075626c69632f696d672f666967757265342e6a7067"><img src="https://camo.githubusercontent.com/6197ef9a1041f279b841b3164271cc4294044e845c5c6ee8acee1d95519ccb43/687474703a2f2f676962736f6e2e766973696f6e2f7075626c69632f696d672f666967757265342e6a7067" width="600" data-canonical-src="http://gibson.vision/public/img/figure4.jpg" style="max-width: 100%;"></a></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更多细节：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于点云渲染存在所有缺陷，事实证明很难通过神经网络修复来获得完全逼真的渲染。</font><font style="vertical-align: inherit;">剩下的问题使得合成图像和真实图像之间存在域差距。</font><font style="vertical-align: inherit;">因此，我们将渲染问题表述为形成一个联合空间，确保渲染图像和真实图像之间的对应关系，而不是尝试（不成功地）渲染与真实图像相同的图像。</font><font style="vertical-align: inherit;">这为穿越这些域提供了一条确定性的路径，从而消除了差距。</font><font style="vertical-align: inherit;">我们为目标图像（I_t）添加另一个网络“u”，并定义渲染损失以最小化f（I_s）和u（I_t）之间的距离，其中“f”和“I_s”代表填充神经网络和点云渲染分别输出（参见上图的损失）。</font><font style="vertical-align: inherit;">我们对 f 和 u 使用相同的网络结构。</font><font style="vertical-align: inherit;">函数 u(I) 经过训练，可以改变现实世界中的观察值 I_t，使其看起来像相应的 I_s，从而消除间隙。</font><font style="vertical-align: inherit;">我们将 u 网络护目镜命名为 u 网络护目镜，因为它类似于现实世界中部署的代理的矫正镜片。</font><font style="vertical-align: inherit;">该机制的详细阐述和讨论可以在论文中找到。</font><font style="vertical-align: inherit;">您可以下载函数 u 并在现实世界中部署训练有素的代理时应用它。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了使用护目镜，您最好需要一个带有深度传感器的相机，我们</font></font><a href="https://github.com/StanfordVL/GibsonEnv/blob/master/examples/ros/gibson-ros/goggle.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供了Kinect 的示例。</font><font style="vertical-align: inherit;">训练好的护目镜函数存储在 中</font></font><code>assets/unfiller_{resolution}.pth</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，并且每一个函数都与一个填充函数配对。</font><font style="vertical-align: inherit;">您需要根据使用的填充函数来使用正确的填充函数。</font><font style="vertical-align: inherit;">如果您没有带深度传感器的相机，我们</font></font><a href="https://github.com/StanfordVL/GibsonEnv/blob/master/examples/demo/goggle_video.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也仅提供 RGB 的示例。</font></font></p>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引文</font></font></h1><a id="user-content-citation" class="anchor" aria-label="永久链接：引文" href="#citation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 Gibson Environment 的软件或数据库，请引用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>@inproceedings{xiazamirhe2018gibsonenv,
  title={Gibson {Env}: real-world perception for embodied agents},
  author={Xia, Fei and R. Zamir, Amir and He, Zhi-Yang and Sax, Alexander and Malik, Jitendra and Savarese, Silvio},
  booktitle={Computer Vision and Pattern Recognition (CVPR), 2018 IEEE Conference on},
  year={2018},
  organization={IEEE}
}
</code></pre><div class="zeroclipboard-container">
    
  </div></div>
</article></div>
