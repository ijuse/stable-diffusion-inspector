# stable-diffusion-inspector

从 Stable Diffusion 生成的图片中读取 pnginfo 来获取生成的参数 / Stable Diffusion 模型类别解析

## 运行方法
此方法来自https://github.com/Akegarasu/stable-diffusion-inspector/issues/16

进入你的主机网站目录（我的是/www/wwwroot/）
```
git clone https://github.com/Akegarasu/stable-diffusion-inspector

cd stable-diffusion-inspector
```
然后运行
```
npm i

npm run build
```
部署好以后，使用命令测试运行
```
python3 -m http.server -d dist 10801
```
然后访问你的域名+`:10801`端口，查看是否运行正常

## 宝塔面板的后续操作

宝塔官方教程：https://www.bt.cn/bbs/thread-125161-1-1.html

在这里只说这个项目

进入Python项目，点新建

![](tutorial_img/宝塔面板的设置.png?raw=true)

然后就是等待完成

后面的部署域名和SSL这就不多做赘述了吧

