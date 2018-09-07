## 交流方式

本项目主要使用 Issues / [QQ](https://jq.qq.com/?_wv=1027&k=5EfkM6K) / [Telegram](https://t.me/OIwiki) 进行交流沟通。

Telegram 群组链接为 [@OIwiki](https://t.me/OIwiki) ， QQ 群号码为 [`588793226`](https://jq.qq.com/?_wv=1027&k=5EfkM6K)，欢迎加入。

## 贡献方式

**我们现在在使用 [Projects](https://github.com/24OI/OI-wiki/projects)，这里详细列举了正在做的事情以及待做事项。**

**在开始编写一段内容之前，请查阅 [Issues](https://github.com/24OI/OI-wiki/issues)，确认没有别人在做相同的工作之后，**

**开个 [新 issue](https://github.com/24OI/OI-wiki/issues/new) 记录你要编写的内容。**

### 我之前没怎么用过 GitHub

参与 Wiki 的编写 ** 需要 ** 一个 GitHub 账号， ** 不需要 ** 高超的 GitHub 技巧。

举个栗子，假如我想要修改一个页面内容，应该怎么操作呢？

1. 在 OI Wiki 网站上找到对应页面
2. 点击 正文右上方、目录左侧的 **“编辑此页”** <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg> 按钮
3. （应该已经跳转到了 GitHub 上的对应页面吧？）这时候右上方还会有一个 **“编辑此页”** <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg> 的按钮，点击它就可以在线编辑了
4. 写好了之后点下方的绿色按钮（Propose file change），可能会提示没有权限。不必担心！GitHub 会自动帮你 fork 一份项目的文件并创建 Pull Request
5. 之后点上方的绿色按钮（Create pull request）后，再点一下出现的绿色按钮（Create pull request）。
6. 提交之后就可以等待他人合并或者指出还要修改的地方，当然你也可以给他人的 PR 提出修改意见，或者只是点赞/踩。如果有消息，会有邮件通知和/或网页上的提醒（取决于在你个人 Settings 中的设置）。

（有木有很简单？）

如果还是不放心，可以参考这篇文章：https://juejin.im/entry/56e638591ea49300550885cc

### 我之前用过 GitHub

基本协作方式如下：

1. Fork 主仓库到自己的仓库中。
2. 当想要贡献某部分内容时，请务必仔细查看 **Issues**，以便确定是否有人已经开始了这项工作。当然，我们更希望你可以加入 QQ / Telegram 群组，方便交流。
3. 在决定将内容推送到本仓库时，** 请你首先拉取本仓库代码进行合并，自行处理好冲突，同时确保在本地可以正常生成文档 **，然后再将分支 PR 到主仓库的 master 分支上。其中，PR 需要包含以下基本信息   
  标题：本次 PR 的目的（做了什么工作，修复了什么问题）  
  内容：如果必要的话，请给出对修复问题的叙述

## 贡献文档要求

当你打算贡献某部分的内容时，你应该尽量确保

- 文档内容满足基本格式要求
- 文档的合理性
- 文档存储的格式

### 文档内容的基本格式

这里主要是指 [中文排版指南](https://github.com/ctf-wiki/ctf-wiki/wiki/%E4%B8%AD%E6%96%87%E6%8E%92%E7%89%88%E6%8C%87%E5%8D%97) 与 [MkDocs 使用说明](https://github.com/ctf-wiki/ctf-wiki/wiki/Mkdocs-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)。后者额外介绍了 mkdocs-material 主题的插件使用方式。

如果对 mkdocs-material （我们使用的这个主题）还有什么问题，还可以查阅 [cyent 的笔记](https://cyent.github.io/markdown-with-mkdocs-material/)，他有介绍 markdown 传统语法和 mkdocs-material 支持的扩展语法。

### 文档的合理性

所谓合理性，指所编写的 ** 内容 ** 必须具有如下的特性

- 由浅入深，内容的难度应该具有渐进性。
- 逻辑性，对于每类内容的撰写应该尽量包含以下的内容
   - 原理，说明该内容对应的原理。
   - 例子，给出 1 ~ 2 个典型的例子。
   - 题目，在该标题下， ** 只需要给出题目名字、题目链接 **

### 文档存储的格式

对于每类要编写的内容，对应的文档应该存储在合适的目录下

- images， 存储文档介绍时所使用的图片，位置为所添加的目录下（即格式为 `![](./images/xx.jpg)`）。
- ** 文件名请务必都小写，以 `-` 分割， 如 `file-name`**

## F.A.Q.

### 目录在哪

目录在项目根目录下的 [mkdocs.yml](https://github.com/24OI/OI-wiki/blob/master/mkdocs.yml#L17) 文件中。

### 如何修改一个 topic 的内容

在对应页面右上方有一个编辑按钮 <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"></path></svg> ，点击之后会跳转到 GitHub 上对应文件的位置。

或者也可以自行阅读目录 [(mkdocs.yml)](https://github.com/24OI/OI-wiki/blob/master/mkdocs.yml#L17) 查找文件位置

### 如何添加一个 topic

1. 可以开一个 Issue，注明希望能添加的内容
2. 可以开一个 Pull Request，在目录 [(mkdocs.yml)](https://github.com/24OI/OI-wiki/blob/master/mkdocs.yml#L17) 中加上新的 topic，并在 [docs](https://github.com/24OI/OI-wiki/tree/master/docs) 文件夹下对应位置创建一个空的 `.md` 文件。

!!! warning "注意"
    写 .md 文件时，请勿在开头写上标题

### commit message 怎么写

我们推荐使用 [commitizen/cz-cli](https://github.com/commitizen/cz-cli) 来规范 commit message （并非强求）。

### 我尝试访问 GitHub 的时候遇到了困难

推荐在 hosts 文件中加入如下几行：（来源： [@GoogleHosts](https://github.com/googlehosts/hosts/blob/master/hosts-files/hosts#L481-L485)）

```
## GitHub Start
192.30.253.118	gist.github.com
192.30.253.112	github.com
192.30.253.112	www.github.com
## GitHub End
```

可以在 [@GoogleHosts 主页](https://github.com/googlehosts/hosts) 上了解到更多信息。

### 我这里 pip 也太慢了

可以选择更换国内源，参考： 	https://blog.csdn.net/lambert310/article/details/52412059

或者：

```bash
pip install -U -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple/
```

### 我在客户端 clone 了这个项目，速度太慢

如果有安装 `git bash`，可以加几个限制来减少下载量：

```bash
git clone https://github.com/24OI/OI-wiki.git --depth=1 -b master
```

参考这篇文章：https://blog.csdn.net/FreeApe/article/details/46845555

### 我没装过 Python 3

可以访问 [Python 官网](https://www.python.org/downloads/) 了解更多信息。

### 好像提示我 pip 版本过低
进入 cmd / shell 之后

```bash
python -m pip install --upgrade pip
```

### 我安装依赖失败了

检查一下：网络？权限？查看错误信息？

### 我已经 clone 下来了，为什么部署不了

检查一下是否安装好了依赖？

### 我 clone 了很久之前的 repo，怎么更新到新版本呢

参考：https://help.github.com/articles/syncing-a-fork/

### 如果是装了之前的依赖怎么更新

```bash
pip install -U -r requirements.txt
```

### 我的数学公式怎么乱码了

如果是行间公式（用的 `$$`），目前已知的问题是需要在 `$$` 两侧留有空行。格式如下：

```
// 空行
$$ a_i $$
// 空行
```

### 为什么我的 markdown 格式乱了

可以查阅 [cyent 的笔记](https://cyent.github.io/markdown-with-mkdocs-material/)，或者 [MkDocs 使用说明](https://github.com/ctf-wiki/ctf-wiki/wiki/Mkdocs-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)。

### 如何给一个页面单独声明版权信息

参考 [Metadata](https://squidfunk.github.io/mkdocs-material/extensions/metadata/#usage) 的使用，在页面开头加一行即可。

比如：

```
copyright: SATA
```

注：默认的是 ‘CC BY-SA 4.0 和 SATA’

### 如何给一个页面关闭字数统计

参考 [Metadata](https://squidfunk.github.io/mkdocs-material/extensions/metadata/#usage) 的使用，在页面开头加一行即可。

比如：

```
pagetime:
```

注：默认的是开着的

### GitHub 是不是不显示我的数学公式？

是的，GitHub 的预览不显示数学公式。但是请放心，mkdocs 是支持数学公式的，可以正常使用，只要是 mathjax 支持的句式都可以使用。

### 我的公式为什么在目录里没有正常显示？好像双倍了？

是的，这个是 python-markdown 的一个 bug，可能近期会修复。

如果现在想要避免目录中出现双倍公式，可以参考 https://github.com/24OI/OI-wiki/blame/master/docs/string/sam.md#L82

```
### 结束位置 <script type="math/tex">endpos</script>
```

在目录中会变成

```
结束位置 endpos
```

【注】：现在请尽量避免在目录中引入 mathjax 公式
