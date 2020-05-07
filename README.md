# cdn
静态资源管理

## github + jsdeliver 搭建免费cdn

### 手动上传资源
1. 点击release发布
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/jsdeliver/1.jpg)

2. 定义版本号及其发布
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/jsdeliver/2.jpg)
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/jsdeliver/3.jpg)

```demo
https://cdn.jsdelivr.net/gh/luchuanqi/cdn/js/dragula.modify.js
```

### picgo
1. 新建repository
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/1-1.jpg)
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/1-2.jpg)
2. 设置
    1. setting
    2. developer settings
    3. create token
    4. copy token
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/2-1.jpg)
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/2-2.jpg)
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/2-3.jpg)
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/2-4.jpg)
3. 安装picgo
    + 设定仓库名：按照【用户名 / 图床仓库名】的格式填写
    + 设定分支名：【master】
    + 设定Token：粘贴之前生成的【Token】
    + 指定存储路径：填写想要储存的路径，如【img/】，这样就会在仓库下创建一个名为 img 的文件夹，图片将会储存在此文件夹中
    + 设定自定义域名:
     ```demo
     https://cdn.jsdelivr.net/gh/用户名/图床仓库名/图片路径
     https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/test/1.jpg
     ```
![](https://cdn.jsdelivr.net/gh/luchuanqi/cdn/images/picgo/3-1.jpg)     

