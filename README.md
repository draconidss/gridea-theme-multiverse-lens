## Multiverse

![](https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/multiverse.jpg)

演示链接：[Multiverse](https://lifealsoisgg.github.io/photos.lifeisgg.online)

## Lens

![](https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/lens.jpg)

演示链接：[Lnes](https://lifealsoisgg.github.io/demo.photos)

# 介绍

一款基于 HTML5 UP 的 Multiverse 与 Lens 模板开发并支持cdn [jsdelivr](https://www.jsdelivr.com/)加速的Gridea 主题。

# 特色
- 同时兼容 Multiverse(多次元) 与 Lens(棱镜) 模板，在设置中即可修改。

- 添加jsdelivr cdn加速github pages功能：在在基础配置中域名填写为

  ```
  https://cdn.jsdelivr.net/gh/github用户名/仓库名
  ```

  并在自定义配中开启并填好jsdelivr相关信息

  > 注意，开启后本地预览时css和js不会被加载，第一次需要同步到仓库后才能加载css和js资源
  
- 举一反三：使用又拍云的webp智能判断

  ![](https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/webp.jpg)

  开通又拍云的云存储功能，然后开启此功能，然后在右上角的文件管理中==创建目录post-images==，之后把博客本地文件夹中的==post-images==中的图片上传上去

  ![](https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/上传文件.jpg)

  然后获取域名

  ![](https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/域名.jpg)

  将仅供测试的域名复制到gridea中远程连接的域名上，到时候渲染的时候就能直接引用又拍云中云存储的图片的链接，==客户端在访问此链接时会自动执行webp判断功能==。如果自己有域名，可以解析CNAME到他给你CNAME地址的，然后将这个域名填写到远程连接中即可。

  本地图片上传时，要把在==post-images==中的图片上传到又拍云，你也可以直接把图片上传到又拍云然后外链引入图片

  最终实测webp减少流量对比

  <div align=center>  
    <table><tr>    
      <img width="50%" src=https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/没有webp.jpg/>    
      <img width="50%" src=https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/有webp.jpg/>    
      </tr></table>
  </div>

  别担心，webp格式与普通jpg差别肉眼难以分辨

- 最后一点，由于远程中的域名被改，所以如果你的网站有下一页，那么可能会链接到==域名/page/2==，而这个域名不是你真实网址，所以请自行更改链接，在==output/index.html==中

  ![](https://cdn.jsdelivr.net/gh/lifealsoisgg/gridea-theme-multiverse-lens/images/翻页.jpg)



​		记得==output/page/2/index.html==中要把上一页改链接，同理如果你有好几页可能要麻烦你去更改。

# 参考

- [HTML5 UP / Multiverse](https://html5up.net/multiverse)
- [getgridea / gridea-theme-starter](https://github.com/getgridea/gridea-theme-starter)
- [wclk / time](https://github.com/wclk/time)
- [getgridea / gridea-theme-notes](https://github.com/getgridea/gridea-theme-notes)
- [hsxyhao / gridea-theme-next](https://github.com/hsxyhao/gridea-theme-next)
- [HTML5 UP / Lens](https://html5up.net/lens)

# 联系

Email：1138312802@qq.com



注：本主题是在主题[gridea-theme-cplayer-gallery](https://github.com/CPlayer-CN/gridea-theme-cplayer-gallery)进行的二次修改