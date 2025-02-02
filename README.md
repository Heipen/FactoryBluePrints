![](https://img.shields.io/github/languages/code-size/DSPBluePrints/FactoryBluePrints?style=for-the-badge)
![](https://img.shields.io/github/last-commit/DSPBluePrints/FactoryBluePrints?style=for-the-badge)

# 戴森球计划 工厂蓝图 | Dyson Sphere Program Factory Blueprint

**!!!强烈建议完整阅读说明!!!**  
**!!!强烈建议完整阅读说明!!!**  
**!!!强烈建议完整阅读说明!!!** <br>
**!!!Highly recommend reading the instructions in full!!!**
**!!!Highly recommend reading the instructions in full!!!**
**!!!Highly recommend reading the instructions in full!!!**

---

## 简介 | Introduction


这是游戏[**戴森球计划**](https://store.steampowered.com/app/1366540/_/)中的蓝图仓库，用于储存与分享来自社区的工厂蓝图  
This is the blueprint repository in the game [**Dyson Sphere Program**](https://store.steampowered.com/app/1366540/_/), used to store and share Factory blueprints from the community

最早一批蓝图主要由**小马蓝图群**成员与**CIDT设科院**成员贡献。为了对来自社区的庞大数量的蓝图进行分类、管理、储存与分享，我们打算将蓝图上传到github作为交流群文件的备份，并且将来可能进一步建设成为蓝图网。  
The first batch of blueprints were mainly contributed by members of **小马蓝图群** and **Cosmical Institute of Design and Technology**. In order to classify, manage, store and share a large number of blueprints from the community, we plan to upload the blueprints to github as a backup of the QQ group files, and may further build a blueprint network in the future.  

您可以加入交流群并将蓝图上传到群文件，我们将不定时将群文件中的蓝图分类上传到仓库中，如有遗漏可以在群里提醒我们。您也可以通过pull request的形式直接投稿，请根据蓝图功能投稿到最合适的文件夹。  
You can join the QQ group and upload the blueprint to the group file. We will classify and upload the blueprint in the group file to the warehouse from time to time. If there is any omission, you can remind us in the QQ group. You can also submit directly in the form of pull request, please submit to the most appropriate folder according to the blueprint function.

除了github，您可以通过这些方式联系我们： (QQ群)  
Except for github, you can contact us in these ways: (QQ Group)

```text
914523440 小马蓝图5群
611954295 小马蓝图4群
342139527 小马蓝图3群
949098605 小马蓝图2群

150369431 CIDT学院群

162065696 戴森球计划蓝图仓库（蓝图仓库维护群）
```

---

## 蓝图仓库使用方法 | How to use the blueprint warehouse

> 蓝图仓库已集成Git与自动更新脚本，无需任何基础也可以正常使用 <br>
> The blueprint warehouse has integrated Git and automatic update scripts, which can be used normally without any foundation

### 第一次下载 | First Download

1. 在电脑上打开github上的蓝图仓库主页: https://github.com/DSPBluePrints/FactoryBluePrints <br>
Open the blueprint warehouse homepage on github on your computer: https://github.com/DSPBluePrints/FactoryBluePrints
2. 从这个页面->[**Releases**](https://github.com/DSPBluePrints/FactoryBluePrints/releases)<-，下载最新的蓝图包，文件名应该叫`FactoryBluePrints_X.Y.Z.7z`，请**不要**从绿色的Code处下载，那样文件不！完！整！<br>
From this page ->[**Releases**](https://github.com/DSPBluePrints/FactoryBluePrints/releases)<-, download the latest blueprint package, the file name should be `FactoryBluePrints_X.Y.Z.7z`, please **DO NOT** download from the green Code, that file will not work! over! all!
3. 解压后，像其他普通的蓝图包一样，放入游戏的默认蓝图文件夹。放进去以后应该是这样：`C:\Users\％用户资料％\Documents\Dyson Sphere Program\Blueprint\FactoryBluePrints\README.md` <br>
After decompression, put it into the game's default blueprint folder like any other normal blueprint package. After putting it in, it should look like this: `C:\Users\%userprofile%\Documents\Dyson Sphere Program\Blueprint\FactoryBluePrints\README.md`

### 更新 | Update

1. 只需双击即可：`双击更新蓝图仓库.bat` <br>
Just double click: `双击更新蓝图仓库.bat`

> Q: 为什么我打不开蓝图仓库主页 / 下载特别慢 / 更新特别慢？<br>
Why can't I open the homepage of the blueprint warehouse / the download is very slow / the update is very slow?
> A: 通常是网络问题。蓝图仓库被托管在github上，可以通过在[Watt Toolkit](https://steampp.net)(原名steam++)中开启github加速服务解决。~~或者魔法？~~ <br>
A: Usually a network problem. The blueprint warehouse is hosted on github, which can be resolved by enabling the github acceleration service in [Watt Toolkit](https://steampp.net) (formerly known as steam++). ~~ Or magic? ~~

<!--

### 以下内容已过时，出于信息完整性考虑暂不删除，但是已经隐藏

### 视频教程

内容同下方的文字教程，视频时长约1.5min  
https://www.bilibili.com/video/bv1RK411Z7b2  

---

### 文字教程

#### 基础用法

您可以直接进入[蓝图仓库的网页](https://github.com/DSPBluePrints/FactoryBluePrints)，寻找并打开自己需要的蓝图文件，点击位于蓝图代码右上方的**全选复制**(Copy raw contents)。  
然后进入游戏，在蓝图页面依次点击**新建空蓝图**，**粘贴**，**保存更改**，就可以将蓝图代码保存到本地，像平常那样使用。  

> 常见问题：  
> Q: 为什么蓝图仓库网页打开特别慢，我该怎么办？  
> A: 蓝图仓库被托管在github上，可以通过在[Watt Toolkit](https://steampp.net)(原名steam++)中开启github加速服务解决。~~或者魔法？~~  

#### 进阶用法

如果您有[Git](https://git-scm.com/)的使用基础，**可以将整个蓝图仓库用`clone`命令拉取到游戏的蓝图文件夹内**。这样您将以蓝图合集的形式将完整的蓝图仓库下载到本地，并且可以在游戏内直接访问，享受在线蓝图仓库与游戏无缝衔接的体验。  

```cmd
git clone https://github.com/DSPBluePrints/FactoryBluePrints.git
```

> 常见问题：  
> Q: `error: SSL_read` 相关  
> A: 通常是网络波动，重试即可。如果已经排除网络问题可以搜索 `git SSL_read` 并逐一排查错误原因，此处不再赘述  

除非你真的非常清楚你正在做什么，否则请不要手动修改`.git`文件夹内的任何文件，这可能导致以后的自动更新出错  

可以通过`pull`命令进行对本地蓝图文件夹进行更新。Git将自动检查上次更新以来发生变动的蓝图/蓝图合集，并以增量更新的形式更新本地仓库  
**或者直接双击仓库根目录下的"双击更新蓝图仓库.bat"**  

```cmd
git pull origin main
```
-->

---

## 协议 | Protocol

1. 如果蓝图作者对自己的蓝图发布使用协议，则自从使用协议发布起，对相关蓝图使用蓝图作者发布的使用协议。<br>
If the blueprint author publishes a usage agreement for his own blueprint, the usage agreement published by the blueprint author will be used for the relevant blueprint since the usage agreement is released.
2. 若无特殊声明，蓝图仓库内的一切蓝图及其他文件使用默认协议：**知识共享 署名-非商业性使用-相同方式共享 4.0 国际(CC BY-NC-SA 4.0)**。<br>
Unless otherwise stated, all blueprints and other files in the blueprint repository use the default license: **Creative Commons Attribution-Non-Commercial-Share Alike 4.0 International (CC BY-NC-SA 4.0)**.