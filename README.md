# Figurebed
This is a figurebed belongs to weitermachen
pora安装很简单

[安装文件](https://pan.baidu.com/s/1RhFRciPPvignG5MeZ2AVbA)

提取码：weit

![安装文件](https://raw.githubusercontent.com/weitermachen/RepositoryName/main/img/image-20220627092426466.png)

安装文件如图，按照使用说明直接安装即可

## PicGo安装

1. 为什么要用PicGO呢（可以不装，装了会更加好用 ）

   Typora的不足：在使用Typora时，对于文档里面的图片，在将文档迁移到其他电脑上面展示时需要将图片一起复制过去带来成本的增加。

   而PicGo是一款图片的上传工具，支持的有微博图床、七牛图床、GitHub图床等等，正好能解决这一问题。其解决问题的大概思路是，将本地的文件或者是剪切板上面的截图发送到图床，然后生成在线图片的链接，这样就可以让Markdown起飞。

2. 下载PicGo

   PicGo下载安装巨简单，直接去GitHub上下载即可，以下放链接，这里下载的2.3.0版本，Window用户直接下载这个即可

   ![下载文件](https://raw.githubusercontent.com/weitermachen/RepositoryName/main/img/image-20220627094627875.png)

   [PicGo2.3.0](https://github.com/Molunerfinn/PicGo/releases/t	ag/v2.3.0)

## GitHub图床

> 注：github访问会比较慢，加速的方法有许多，最直接暴力的就是花钱买vpn了，然后还有就是使用更改hosts的方法，在后面会单独介绍一下更改hosts加速github的方法

1. 注册/登录GitHub账号

  ![GitHub注册](https://raw.githubusercontent.com/weitermachen/RepositoryName/main/img/image-20220627100634973.png)

  注册很简单，进入github后点击sign up直接按照提示 进行注册即可。

2. 创建Repository

   - 点击New按钮

     ![第一步](https://raw.githubusercontent.com/weitermachen/RepositoryName/main/img/image-20220627100949885.png)

   - 出现如下界面，按照1、2、3、4进行即可，1、2中按照自己的想法取名和说明即可，3中为生成README文档，非必选，他这里创建的默认分支名为main(后面进行配置的时候会用到这个名字，因为默认分支名的原因在进行配置时我出现了很多错误)

     ![开始创建库](https://raw.githubusercontent.com/weitermachen/RepositoryName/main/img/image-20220627101532047.png)

3. 生成操作repository的一个私人访问token(最为重要的一个步骤)

   - 
